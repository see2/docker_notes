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

```
docker inspect xxx
```

### Splash


(open docker)
```
docker pull scrapinghub/splash
docker run -it -p 8050:8050 scrapinghub/splash
```

and in python

```pip install scrapy-splash```


### Install anaconda

- In mainland:

```
wget https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/Anaconda3-5.3.1-Linux-x86_64.sh
bash Anaconda3-5.3.1-Linux-x86_64.sh

sudo vim /etc/profile
# change path
PATH=/home/user/anaconda3/bin:$PATH
# maybe the path is different
source /etc/profile
# apply change
```
I failed two times, maybe caused by the incomplete package.


### GitHub

linux server connect to github using ssh:

https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


### RSA(SSH)

change some setting to allowed use ssh to pass the public key:
- https://www.digitalocean.com/community/questions/error-permission-denied-publickey-when-i-try-to-ssh

pass the public key to server:
- https://askubuntu.com/questions/311558/ssh-permission-denied-publickey

### Jupyter lab 

connection:
- https://agent-jay.github.io/2018/03/jupyterserver/

### ipad

termius on ios or ipados


### Other vitual environment

- Conda

A article compare conda/miniconda/virtualenv [here](http://deeplearning.lipingyang.org/2018/12/23/anaconda-vs-miniconda-vs-virtualenv/)

