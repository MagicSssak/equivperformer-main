

Command this

```
python3 nbody_run.py --ri_delta_t 10 --num_degrees 4 --batch_size 128 --num_channels 8 --div 4 --ri_burn_in 0 --siend att --xij add --head 2 --data_str 20_new --print_interval 100 --lr 3e-3 
```

This is for reload
```
--restore ./models/ri_dgl.pt
--restore ./pretrain/ri_dgl.pt
```
remove selfint
```
--siend 1x1  
--simid 1x1  
```

 add selfint
```
--siend att 
--simid att 
```


 use performer
 adjust max number of random features and antithetic or not
```
--Performer --max_rf 8 --antithetic
```
# equivperformer-main