# exploring some pipeline data

## source

distribution, transmission & gathering, lng, and liquid annual data set from the pipeline and hazardous materials safety administration
- [gas distribution annual data 2010-2017](https://www.phmsa.dot.gov/data-and-statistics/pipeline/distribution-transmission-gathering-lng-and-liquid-annual-data)

## running

1. `docker pull jeremiak/pandas-notebook`
1. `docker run -it --rm -p 8888:8888 -v $PWD:/work jeremiak/pandas-notebook`
1. jupyter notebook server running at port 8888
