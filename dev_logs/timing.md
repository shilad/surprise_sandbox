# Timing

## 3/27
### ml-1m
`python sandbox.py --dataset ml-1m --grouping sample --sample_sizes 10 --num_samples 60`

Full runtime was: 3695.9246697425842 for 60 runs

3696 / 60
61.6 sec/run

Full runtime was: 2546.780566215515 for 54 runs
47

### ml-100k
`python sandbox.py --dataset ml-100k --grouping individual_users`
Full runtime was: 2039.7360241413116 for 1 runs


## 3/28
python sandbox.py --grouping sample --num_samples 100 --sample_sizes 2,4,8
Full runtime was: 13894.118345737457 for 300 runs
