# SHOME-BIO

SHOtgun MEtagenomic analysis of BIOlogical entities (SHOME-BIO) is a dockerized solution for metagenomics. Inside a docker container, we installed UBUNTU with python 3.7 and Anaconda 3 (V. 2020/02).
Inside an anaconda base environment, we installed two common metagenomics software, KAIJU (http://kaiju.binf.ku.dk/) and KRAKEN (https://ccb.jhu.edu/software/kraken/), and other mandatory softwares for the pipeline. For the complete list, please read our paper here (link)


## 1 - DOCKER INSTALLATION

To use our pipeline, it is mandatory to install and run DOCKER (https://hub.docker.com/). Here (https://hub.docker.com/search?q=&type=edition&offering=community) you can find the correct version of DOCKER for your OS and all the infos about how to install and run docker. 


## 2 - PIPELINE INSTALLATION

Run DOCKER on your PC or server and download and install our pipeline pulling it from here (https://hub.docker.com/r/biohaz/metagenomic) or just type:
```
docker pull biohaz/shome_bio:latest
```


## 3 - BEGIN THE ANALYSIS

### 3.1 Prepare the Config file

To run the pipeline, just manually change the "config.txt" file to choose the correct options for your analysis. You can find an example of "config file" in this repository.

### 3.2 - Download the databases

In order to run a metagenomic analysis, you should download different genome reference for bacteria and virus.
You can download them directly from here
```
http://
```

You can also download a test data folder with two .fastq files here ()



## 4 - LICENSE
This is a free pipeline: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.