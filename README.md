# NIHCloudLab
NIH Cloud Lab is a resource developed by NIH’s CIT Cloud Services Team to support STRIDES’ mission of enabling and modernizing biomedical research through the cloud. Through this resource, NIH-funded researchers can become more efficient and comfortable in leveraging the cloud for their research purposes.

We offer Cloud Lab for each of the three big Cloud Service Providers, and we have a separate GitHub repository for each one. Visit these repositories for more information and collections of tutorials for [AWS](https://github.com/STRIDES/NIHCloudLabAWS), [Azure](https://github.com/STRIDES/NIHCloudLabAzure), and [Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP).


We have compiled a variety of tutorials from different sources to help you navigate through various research methods using cloud platforms. These tutorials cover a wide range of topics including biomedical workflows, artificial intelligence, medical imaging, and more. Each tutorial is designed to guide you through specific tasks using services from three major cloud service providers: Azure, AWS, and GCP. Whether you are working with a virutual machine, using a familiar evironment like Jupyter notebooks, or other cloud managed services, these tutorials will provide you with the necessary steps and insights to efficiently accomplish your research goals. A few of the tutorials available in our tutorial repositories are highlighted below. Please navigate to our CSP-specific repositories to find the full list of available tutorials. Let's dive in to the exciting world of cloud computing!


## General Set Up

NIH employees and affiliates may request a free Cloud Lab account. These accounts may be provisioned for AWS, GCP or Azure and come with $500 of cloud credits, which are valid for up to 90 days. To find instructions on how to request an account please visit the [NIH Cloud Lab](https://cloud.nih.gov/resources/cloudlab/) information page. 

If you have any questions, you may reach out to the cloud lab team at cloudlab@nih.gov or refer to our [FAQ page](https://cloud.nih.gov/resources/cloudlab/cloudlab-faqs/). 

## Table of Contents
- [Artificial Intelligence](#artificial-intelligence)
- [Biomedical Workflows](#biomedical-workflows)
- [Clinical Informatics](#clinical-informatics)
- [GWAS](#gwas)
- [Medical Imaging](#medical-imaging)
- [RNASeq](#rnaseq)
- [Single Cell RNASeq](#single-cell-rnaseq)
- [ElasticBlast](#elasticblast)
- [Protein Folding](#protein-folding)
- [Long Read Sequencing](#long-read-sequencing)
- [Drug Discovery](#drug-discovery)

## Artificial Intelligence

Artificial Intelligence (AI) and Generative AI are revolutionizing the way we interact with technology, offering unprecedented opportunities for innovation and automation. Whether you're a beginner or an advanced user, these tutorials will guide you through the latest advancements in AI, helping you harness its potential. Learn how to [deploy models using Vertex AI on the GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/GCP_GenAI_Huggingface.ipynb), [create a PubMed Chatbot using Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/notebooks/Pubmed_RAG_chatbot.ipynb), and utilize an AI playground like [Bedrock on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/AWS_Bedrock_Intro.ipynb). Our tutorials guide you through the new an emerging field of AI on the most popular cloud platforms. To explore more tutorials in this topic, please visit the cloud platform repositories:

- [Generative AI on GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/)
- [Generative AI on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/)
- [Generative AI on Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/)

 
## Biomedical Workflows

This section includes tutorials and resources for running various biomedical workflows using cloud platforms. Popular workflow languages such as Nextflow and Snakemake are run in cloud-based HPC environments. Learn how to efficiently run workflows on AWS, GCP, and other platforms, leveraging tools like [AWS's ParallelCluster](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/Snakemake/AWS-ParallelCluster.ipynb), [Google Batch](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GoogleBatch/nextflow/Part2_GBatch_Nextflow.ipynb), and more.

- [Google Batch](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GoogleBatch/)
- [AWS Batch](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/AWSBatch/)
- [AWS Parallel Cluster](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/Snakemake)


## Clinical Informatics

This section focuses on the application of AI in clinical settings. Learn about [Google Cloud's MedLM](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/GCP_MedLM_Intro.ipynb) and [Azure's AI Studio](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/Azure_AI_Studio_README.md). These tutorials can be found in the Genarative AI section's in our tutorial repositories. 


## GWAS

Discover resources for conducting Genome-Wide Association Studies (GWAS) on various cloud platforms. This section includes tutorials on running GWAS workflows using deep learning techniques and cloud-based tools like [Kubeflow on GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/DL-gwas-gcp-example/1-d10-run-first.ipynb) and [AWS's EC2](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GWAS/GWAS_coat_color.ipynb). 


## Medical Imaging

Learn about medical imaging techniques and tools in this section. It includes resources for using pre-trained models to run a custom [Spleen Segmentation model on GCP](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/SpleenLiverSegmentation), [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/SpleenLiverSegmentation/SpleenSeg_Pretrained-4_27.ipynb) and [Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/SpleenLiverSegmentation/SpleenSeg_Pretrained-4_27.ipynb).


## RNASeq

This section provides resources for RNA-Seq analysis on different cloud platforms. It includes tutorials for running [RNA-Seq pipelines on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/rnaseq-myco-tutorial-main/RNAseq_pipeline.ipynb) and [Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/rnaseq-myco-tutorial-main/RNAseq_pipeline.ipynb) , helping you run a familiar pipeline using cloud technology. 


## Single Cell RNASeq

Explore single-cell RNA sequencing (scRNA-Seq) techniques in this section. It includes tutorials for running the [Pangolin SARS-CoV-2 pipeline on Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb), [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb), and [Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb), enabling detailed analysis of single-cell data. 


## ElasticBlast

Learn how to run ElasticBLAST on cloud platforms in this section. It includes tutorials for setting up and executing [ElasticBLAST workflows on Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/elasticBLAST/run_elastic_blast.ipynb) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/ElasticBLAST/run_elastic_blast.ipynb), facilitating large-scale sequence alignment tasks.


## Protein Folding

This section includes resources for protein folding analysis using cloud platforms. It features tutorials on training and [deploying Huggingface models on AWS's SageMaker](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/AWS_GenAI_Huggingface.ipynb)


## Long Read Sequencing

Discover resources for long-read sequencing data analysis in this section. It includes tutorials for downloading sequence data from the [NCBI Sequence Read Archive (SRA) on Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/SRADownload/SRA-Download.ipynb) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/SRADownload/SRA-Download.ipynb), supporting comprehensive genomic studies. 



