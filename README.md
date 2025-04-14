# NIHCloudLab
NIH Cloud Lab is a resource developed by NIH’s CIT Cloud Services Team to support STRIDES’ mission of enabling and modernizing biomedical research through the cloud. Through this resource, NIH-funded researchers can become more efficient and comfortable in leveraging the cloud for their research purposes.

We offer Cloud Lab for each of the three big Cloud Service Providers, and we have a separate GitHub repository for each one. Visit these repositories for more information and collections of tutorials for [AWS](https://github.com/STRIDES/NIHCloudLabAWS), [Azure](https://github.com/STRIDES/NIHCloudLabAzure), and [Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP).


We have compiled a variety of tutorials from different sources to help you navigate through various research methods using cloud platforms. These tutorials cover a wide range of topics including biomedical workflows, artificial intelligence, medical imaging, and more. Each tutorial is designed to guide you through specific tasks using services from three major cloud service providers: Azure, AWS, and GCP. Whether you are working with a virtual machine, using a familiar environment like Jupyter Notebooks, or other cloud-managed services, these tutorials will provide you with the necessary steps and insights to efficiently accomplish your research goals. A few of the tutorials available in our tutorial repositories are highlighted below. Please navigate to our CSP-specific repositories to find the full list of available tutorials. Let's dive into the exciting world of cloud computing!


## General Set Up

NIH employees and affiliates may request a free Cloud Lab account. These accounts may be provisioned for AWS, GCP or Azure and come with $500 of cloud credits, which are valid for up to 90 days. To find instructions on how to request an account please visit the [NIH Cloud Lab](https://cloud.nih.gov/resources/cloudlab/) information page. 

If you have any questions, you may reach out to the cloud lab team at cloudlab@nih.gov or refer to our [FAQ page](https://cloud.nih.gov/resources/cloudlab/cloudlab-faqs/). 

## Table of Contents
- [Machine Learning & Artificial Intelligence](#artificial-intelligence)
  - [Medical Imaging](#medical-imaging)
  - [Generative AI](#genai)
- [Accelerated Biomedical Workflows](#biomedical-workflows)
  - [Workflow Languages](#workflow-languages)
  - [Single Cell RNASeq](#single-cell-rnaseq)
- [Clinical Informatics](#clinical-informatics)
  - [Querying VCF Data](#vcf)
  - [Storing and Analyzing Healthcare Data](#EHR)
  - [Drug Discovery](#drug-discovery)
- [GWAS](#gwas)
- [SARS-CoV-2 Lineage Analyses](#covid)
- [RNASeq](#rnaseq)
- [Long Read Sequencing](#long-read-sequencing)
- (Utilizing SRA Data)(#sra)
- [Blast](#elasticblast)


## Machine Learning & Artificial Intelligence
Machine Learning and Artificial Intelligence (ML/AI) are revolutionizing the way we interact with technology, offering unprecedented opportunities for innovation and automation. Whether you're a beginner or an advanced user, these tutorials will guide you through the latest advancements in AI, helping you harness its potential. Check our repos to learn about how ML/AI can help with **drug discovery** ([Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#drug-discovery-) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#drug-discovery-)), **proteomics** utilizing tools like AlphaFold ([Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#proteomics-) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#protein-folding-)), and medical imaging.

### Medical Imaging
Learn about AI medical imaging techniques and tools in this section. It includes resources for using pre-trained models to run a custom Spleen Segmentation model using NVIDIA Models and MONAI:
- [Vertex AI Workbench in GCP](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/SpleenLiverSegmentation)
- [SageMaker AI Notebooks in AWS](https://github.com/STRIDES/NIHCloudLabAWS/tree/drafts/notebooks/SpleenLiverSegmentation)
- [Machine Learning Studio in Azure](https://github.com/STRIDES/NIHCloudLabAzure/tree/main/notebooks/SpleenLiverSegmentation).

### Generative AI
Learn how to [deploy models using Vertex AI in GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/GCP_GenAI_Huggingface.ipynb), [create a PubMed Chatbot using Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/notebooks/Pubmed_RAG_chatbot.ipynb), and utilize an AI playground like [Bedrock on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/AWS_Bedrock_Intro.ipynb). Our tutorials guide you through the new and emerging field of AI on the most popular cloud platforms. To explore more tutorials on this topic, please visit the cloud platform repositories:

- [Generative AI on GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/)
- [Generative AI on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/)
- [Generative AI on Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/)


## Accelerated Biomedical Workflows
This section provides tutorials and resources for executing a variety of biomedical workflows in the cloud, leveraging popular workflow languages and cloud-based tools to streamline and accelerate processing.

### Workflow Languages
Nextflow and Snakemake in cloud-based Batch and HPC environments. Learn how to accelerate and efficiently run workflows on AWS, GCP, and other platforms, leveraging tools like [AWS's ParallelCluster](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/Snakemake/AWS-ParallelCluster.ipynb), [Google Batch](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GoogleBatch/nextflow/Part2_GBatch_Nextflow.ipynb), and more.

- [Google Batch](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GoogleBatch/)
- [AWS Batch](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/AWSBatch/)
- [AWS Parallel Cluster](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/Snakemake)
- [Azure Batch](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#microsoft-genomics-)

### Single Cell RNASeq
Explore single-cell RNA sequencing (scRNA-Seq) techniques to run an accelerated scRNAseq pipeline using RAPIDS on [Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#single-cell-rnaseq-), [AWS](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#single-cell-rnaseq-), and [Azure](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#single-cell-rnaseq-), enabling detailed analysis of single-cell data. 


## Clinical Informatics
Discover resources and techniques that aid Clinical Informatics to improve healthcare delivery, patient outcomes, and clinical decision-making bridging the gap between healthcare, technology, and data science by designing, implementing, and optimizing systems that manage clinical information. You can check out the various tutorials below to provide practical insights and tools to help you effectively leverage technology and data in healthcare.
### Querying VCF Data
 - [Google Cloud's Big Query](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#query-a-vcf-file-in-big-query-)
 - [Azure Synapse](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#vcf)
### Storing and Analyzing Healthcare Data
 - [FHIR in Azure](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#clinical-informatics-with-fhir-)
 - [AWS HealthLake](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#clinical-informatics-)
### Accelerating Drug Discovery with ATOM
 - [Google Cloud Vertex AI](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#drug-discovery-)
 - [AWS SageMaker AI](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#drug-discovery-)


## GWAS
Discover resources for conducting Genome-Wide Association Studies (GWAS) on various cloud platforms. This section includes tutorials on running GWAS workflows using deep learning techniques and cloud-based tools like:
- [GCP's Vertex AI Workbench](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GWASCoatColor/GWAS_coat_color.ipynb) or [Kubernetes on GCP](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/DL-gwas-gcp-example) to deploy a machine learning pipeline using Kubeflow
- [AWS's EC2](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GWAS/GWAS_coat_color.ipynb)
- [Azure's Machine Learning Studio](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GWAS/GWAS_coat_color.ipynb)


## SARS-CoV-2 Lineage Analyses 
Learn how to run a standard COVID bioinformatics pipeline using the Pangolin workflow all within a cloud Jupyter environment for [GCP](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb), [Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb), and [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/pangolin/pangolin_pipeline.ipynb).


## RNASeq
This section provides resources for RNA-Seq analysis on different cloud platforms. It includes tutorials for running [RNA-Seq pipelines on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/rnaseq-myco-tutorial-main/RNAseq_pipeline.ipynb) and [Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/rnaseq-myco-tutorial-main/RNAseq_pipeline.ipynb), helping you run a familiar pipeline using cloud technology. 


## Long Read Sequencing
Long-read DNA sequence analysis focuses on processing sequencing reads that are typically over 10,000 base pairs (bp) in length, in contrast to short-read sequencing, where reads are approximately 150 bp. Oxford Nanopore provides a comprehensive collection of notebook tutorials for working with long-read data, enabling tasks such as variant calling, RNA sequencing (RNA-seq), SARS-CoV-2 analysis, and more.

- [Azure](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#long-read-sequence-analysis-)
- [Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#long-read-sequence-analysis-)
- [AWS](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#long-read-sequence-analysis-)


## Utilizing SRA Data
Discover how to download and analyze SRA data in the cloud from the [NCBI Sequence Read Archive (SRA) on Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/SRADownload/SRA-Download.ipynb) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/SRADownload/SRA-Download.ipynb), supporting comprehensive genomic studies. 


## Blast
Learn how to run BLAST on cloud platforms in this section. It includes tutorials for setting up and executing [ElasticBLAST workflows on Google Cloud](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/elasticBLAST/run_elastic_blast.ipynb) and [AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/ElasticBLAST/run_elastic_blast.ipynb) and how to use [Blast+ in Azure](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#ncbi-blast-) facilitating large-scale sequence alignment tasks.




