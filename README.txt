# FASTQ Dataset Preparation for Disease Classification

## Project Title
FASTQ Dataset Preparation for Breast Cancer Classification

## Project Purpose
This project prepares a biological dataset in FASTQ format for machine learning classification.  
The dataset contains two biological classes: healthy control samples and breast cancer patient samples.  
These sequencing data come from circulating miRNA sequencing experiments and will later be used for bioinformatics analysis such as k-mer extraction and disease classification.

## Dataset Description

Classes used in this project:

Class 0 – Healthy (Control)
SRR37278450
SRR37278459
SRR37278460
SRR37278447
SRR37278458

Class 1 – Breast Cancer (Case)
SRR37278448
SRR37278456
SRR37278461
SRR37278462
SRR37278463

All samples are RNA sequencing datasets from human serum.

Disease: Breast Cancer  
Organism: Homo sapiens  
Sequencing Strategy: miRNA-Seq  
Platform: Illumina NextSeq 500

Dataset obtained from the public repository:
:contentReference[oaicite:0]{index=0}.

## Project Structure

bioinformatics_project/
│
├── data/
│   └── FASTQ files
│
├── README.md
│
└── requirements.txt

data/  
Contains all raw FASTQ sequencing files.

README.md  
Contains the description and documentation of the project.

requirements.txt  
Contains the Python libraries required to run the analysis environment.

## Quick Start Guide

Create virtual environment:

python -m venv bioinfo_env

Activate environment:

bioinfo_env\Scripts\activate

Install required libraries:

pip install -r requirements.txt

## Required Python Libraries

biopython  
pandas  
matplotlib  
seaborn  
scikit-bio

## Dataset Source

Source: NCBI SRA

Project Accession:
SRP678043

Run Accession IDs:

SRR37278448  
SRR37278456  
SRR37278461  
SRR37278462  
SRR37278463  
SRR37278450  
SRR37278459  
SRR37278460  
SRR37278447  
SRR37278458

Study Title:
Integrating circulating microRNAs with epidemiological factors enhances breast cancer detection across subtypes.