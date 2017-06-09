# Week 1: 1. Tools Setup for Linux

> The instructions are specific to Ubuntu operating 

[TOC]

## Java Installation

Check for the java installation using:

```shell
java -version
```

If it's not installed, it can be installed using:

```shell
sudo apt-get install openjdk-8-jdk
```



## SBT Installation

Check for `SBT` installation using:

```shell
sbt about
```

If it's not installed, it can be installed using [instructions from here](http://www.scala-sbt.org/release/docs/Installing-sbt-on-Linux.html):

```shell
echo "deb https://dl.bintray.com/sbt/debian /" | sudo tee -a /etc/apt/sources.list.d/sbt.list
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2EE0EA64E40A89B84B2DF73499E82A75642AC823
sudo apt-get update
sudo apt-get install sbt
```

