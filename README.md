# abstract_classification
# Linux programs for classifying published abstracts and extracting protein names

In the paper "**Compilation of parasitic immunogenic proteins from 30 years of published research using machine learning and natural language processing**", we have developed a computational Linux pipeline that first classifies published abstracts using machine learning (ML), and then extracts protein and/or gene names from the classified ‘abstracts of interest’ using natural language processing (NLP), where ‘abstracts of interest’ is an abstract that potentially contains a protein name of a vaccine candidate. This GitHub repository provides the programs for the pipeline.

## Computer platform used for the development
All experiments and data generation was performed on a high performance computing (HPC) cluster node with 64 bit kernel, 32 MB memory, and 8 cores. The pipeline programs were designed for a Linux operating system and have only been tested on Red Hat Enterprise Linux 7.9, but are expected to work on most Linux distributions. Python version used was 3.6.8.

## To run the pipeline software

Download the latest version from **https://github.com/goodswen/abstract_classification/releases** e.g., download software_v*x.x*.tar.gz (where *x.x* is the latest version number) 

Decompress: **tar –zxvf software_v*x.x*.tar.gz** (where *x.x* is the latest version number)

A parent directory called **abstract_classification** is obtained after decompressing the downloaded file. This directory can be moved to any location of your choice. 

Please refer to the **Instructions PDF** that describes the contents of abstract_classification.

For **HELP**, please e-mail **Stephen.Goodswen@uts.edu.au**
 
