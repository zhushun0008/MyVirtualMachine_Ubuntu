# My VirtualMachine Ubuntu 14.04 LTS

## Basic Configuration 
RAM
Processors

## Basic Tools

### ssh
### Java
```
首先添加ppa

$ sudo add-apt-repository ppa:webupd8team/java
然后更新系统

$ sudo apt-get update
最后开始安装

$ sudo apt-get install oracle-java8-installer
$ java -version
```

## Python

#### Python 2.7
#### Pycharm
#### Tornado
#### Anacona

1. Download the installer.
  * https://www.continuum.io/downloads#_unix
2. bash Anaconda-2.3.0-Linux-x86_64.sh
NOTE: Type "bash" regardless of whether or not you are actually using the bash shell.
3. Optional: Verify data integrity with MD5.



### Redis
1. Install Redis Server
  * Install default version, which most of the time is not a newest version, e.g 2.8
  ```
   sudo apt-get install redis-server
  ```
  * Install Newest version from official site
```
$ wget http://download.redis.io/releases/redis-3.0.5.tar.gz
$ tar xzf redis-3.0.5.tar.gz
$ cd redis-3.0.5
$ make
```
2. Install Redis-cli
```
sudo apt-get install redis-tools
```
### MongoDB



