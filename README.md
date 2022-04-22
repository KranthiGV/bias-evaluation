# Dataset Setup
1. `cd dataset & wget https://github.com/moinnadeem/StereoSet/blob/master/data/dev.json`

# Environment Setup
1. `conda env create -f environment-(cpu/gpu).yml`
2. `conda activate bias-(cpu/gpu)`

#### Saving Changes
- `conda env export -n bias-(cpu/gpu).yml -f environment-(cpu/gpu).yml --no-builds`

### Issues Observed
- Had to clean build info from env files. If it happens again. Follow --> https://stackoverflow.com/a/56780297/3712270
