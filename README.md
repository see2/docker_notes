# docker_notes


### Use Conda

```
conda create -n [nameofenv] python=[version]
conda activate [nameofenv]
conda install anaconda
conda install netcdf4
conda deactivate
```

seldom use conda install netcdf4


### Docker

Install Docker in Windows

Install Docker in ubuntu
https://docs.docker.com/install/linux/docker-ce/ubuntu/

### Splash


(open docker)
```
docker pull scrapinghub/splash
docker run -it -p 8050:8050 scrapinghub/splash
```

and in python

```pip install scrapy-splash```
