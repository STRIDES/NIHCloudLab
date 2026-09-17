# NIH Cloud Lab 

> For NIH-affiliated researchers and trainees exploring cloud-based bioinformatics, AI/ML, and data science workflows in a secure, NIH‑approved environment.

---
## Start Here

- **Learn the program & request an account:** [NIH Cloud Lab](https://cloud.nih.gov/resources/cloudlab/)
- **Extramural account sign‑up instructions:** [Sign up (Extramural)](https://github.com/STRIDES/NIHCloudLab/blob/main/SignUp/extramural_account_registration.md)
- **CSP-specific tutorial repositories:**
  - **AWS:** [STRIDES/NIHCloudLabAWS](https://github.com/STRIDES/NIHCloudLabAWS)
  - **Azure:** [STRIDES/NIHCloudLabAzure](https://github.com/STRIDES/NIHCloudLabAzure)
  - **Google Cloud:** [STRIDES/NIHCloudLabGCP](https://github.com/STRIDES/NIHCloudLabGCP)

> Accounts typically provide **up to $500 in credits** for **up to 90 days** of exploration. Use public/non‑sensitive data only.

---
## What Is NIH Cloud Lab?

NIH Cloud Lab is developed by NIH’s Center for Information Technology (CIT) Cloud Services Team to support the **STRIDES Initiative** mission of modernizing biomedical research through the cloud. It offers short‑term, low‑risk access to AWS, Azure, and Google Cloud along with curated, hands‑on tutorials.

**You’ll get:**
- A temporary cloud account (AWS / Azure / GCP)
- Guardrails for spend tracking and program duration
- Curated tutorials and notebooks for common research tasks
- Guidance on beginner cloud operations and Jupyter environments

---
## Tutorial Catalog (Topics)

Use the CSP repositories for full lists.Highlights include:

### 1. Artificial Intelligence & Machine Learning 
  Cloud‑based AI/ML workflows across Azure, AWS, and GCP. Includes model training, inference, imaging, and Generative AI examples.

#### Subtopics 
- Machine Learning & AI (general workflows, model pipelines)
    - [Drug Discovery](https://github.com/ATOMScience-org/AMPL/tree/master/atomsci/ddm/examples/tutorials)
    - [AlphaFold](https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/community-content/alphafold_on_workbench/AlphaFold.ipynb)
- Medical Imaging (MONAI, NVIDIA models)
    - [Spleen Segmenttion with Liver](https://github.com/STRIDES/NIHCloudLabAzure/tree/main/notebooks/SpleenLiverSegmentation)
- Generative AI (PubMed chatbot, Bedrock, Vertex AI, Azure OpenAI)
    - [PubMed Chatbot](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/notebooks/Pubmed_RAG_chatbot.ipynb)
    - [BedRock](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GenAI/AWS_Bedrock_Intro.ipynb)
    - [Vertex AI HuggingFace](https://github.com/STRIDES/NIHCloudLabGCP/blob/main/notebooks/GenAI/GCP_GenAI_Huggingface.ipynb)
  
To explore more tutorials on this topic, please visit the cloud platform repositories:
- [Generative AI on GCP](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/GenAI)
- [Generative AI on AWS](https://github.com/STRIDES/NIHCloudLabAWS/tree/main/notebooks/GenAI)
- [Generative AI on Azure](https://github.com/STRIDES/NIHCloudLabAzure/tree/main/notebooks/GenAI)
### 2. Biomedical Workflows
Scientific pipelines commonly used in bioinformatics and computational biology.

#### Subtopics 
- RNA‑Seq
    - [RNA-Seq Pipeline on Azure](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/rnaseq-myco-tutorial-main/Bulk_RNA-Seq_pipeline.ipynb)
    - [RNA-Seq Pipeline on GCP](https://nf-co.re/rnaseq/3.7 )
    - [RNA-Seq Pipeline on AWS](https://github.com/STRIDES/NIHCloudLabAWS/tree/main/notebooks/rnaseq-myco-tutorial-main)
- Single‑Cell RNA‑Seq (scRNA‑seq analysis)
    - [scRNA-seq Pipeline](https://github.com/NVIDIA-Genomics-Research/rapids-single-cell-examples/blob/master/notebooks/hlca_lung_cpu_analysis.ipynb)
- Long‑Read Sequencing (Nanopore tutorials)
    - [Analysis](https://epi2me.nanoporetech.com/nbindex/)
- Proteomics (AlphaFold, cloud‑native workflows)
    - [AlphaFold](https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/community-content/alphafold_on_workbench/AlphaFold.ipynb)
    - [Protein Expression](https://github.com/isb-cgc/Community-Notebooks/tree/master/FeaturedNotebooks) 
- Genomics
    - [Genomics Pipeline](https://github.com/microsoft/genomicsnotebook)
    - [Variant Calling](https://deepwiki.com/gatk-workflows/gatk4-data-processing/5.3-google-cloud-platform-setup)
    - [Somatic Varinat Analysis](https://sbc.shef.ac.uk/somatic-variants/index.nb.html)
- GWAS (cloud‑based genotype/phenotype workflows)
    - [GWAS on Azure](https://github.com/STRIDES/NIHCloudLabAzure/tree/main/notebooks/GWAS)
    - [Deep Learning GWAS on GCP](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/DL-gwas-gcp-example)
    - [GWAS on AWS](https://github.com/STRIDES/NIHCloudLabAWS/blob/main/notebooks/GWAS/GWAS_coat_color.ipynb)
- Metagenomics, ATAC‑seq, other multi‑omics pipelines
    - [ATAC-Seq Analysis](https://github.com/NIGMS/ATAC-Seq-and-Single-Cell-ATAC-Seq-Analysis)
    - [Metagenomics Analysis](https://github.com/NIGMS/Metagenomics-Analysis-of-Biofilm-Microbiome)
- SARS‑CoV‑2 lineage workflows
    - [Pangolin Pipeline](https://github.com/STRIDES/NIHCloudLabAWS/tree/main/notebooks/pangolin)
- BLAST & ElasticBLAST
    - [NCBI BLAST on Azure](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/running-ncbi-blast-on-azure-%e2%80%93-performance-scalability-and-best-practice/2410483)
    - [Elastic Blast](https://blast.ncbi.nlm.nih.gov/doc/elastic-blast/quickstart-gcp.html)

### 3. Workflow Languages & Pipeline Orchestration
Cloud execution of workflow languages and HPC‑style batch processing.

#### Subtopics 
- [Nextflow](https://microsoft.github.io/Genomics-Community/mydoc_nextflow.html)
- [Sagemaker](https://github.com/aws/amazon-sagemaker-examples/tree/main/introduction_to_applying_machine_learning)
- [SnakeMake](https://github.com/STRIDES/NIHCloudLabAWS/tree/main/notebooks/Snakemake)
- [Cromwell](https://github.com/microsoft/CromwellOnAzure)
- Platform-specific batch orchestration:
    - [AWS Batch](https://github.com/STRIDES/NIHCloudLabAWS/tree/main/notebooks/AWSBatch)
    - [Google Batch](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/GoogleBatch)
    - [Azure Batch](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#microsoft-genomics-)
    - HPC cluster configuration
          - [AWS](https://docs.aws.amazon.com/solutions/deploying-high-performance-computing-clusters-on-aws/)
          - [GCP](https://docs.cloud.google.com/compute/docs/hpc/overview-hpc-clusters)
          - [Azure](https://learn.microsoft.com/en-us/azure/architecture/guide/compute/high-performance-computing)

### 4.  Clinical & Healthcare Informatics
Tutorials focused on clinical data systems and secure healthcare analytics.     

#### Subtopics
- [FHIR on Azure](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#clinical-informatics-with-fhir-)
- [AWS HealthLake](https://github.com/STRIDES/NIHCloudLabAWS?tab=readme-ov-file#clinical-informatics-)

### 5. Data Retrieval & Cloud‑Native Storage
Accessing public datasets and performing scalable cloud queries.
- [COVID-19 Data Lake](https://learn.microsoft.com/en-us/azure/open-datasets/dataset-covid-19-data-lake)
- [Genome Aggregation Database](https://registry.opendata.aws/broad-gnomad/)
- [Open Data on AWS](https://registry.opendata.aws/)

#### Subtopics
- [SRA Data (NCBI)](https://github.com/STRIDES/NIHCloudLabGCP/tree/main/notebooks/SRADownload)
- [BigQuery]( https://github.com/STRIDES/NIHCloudLabGCP?tab=readme-ov-file#query-a-vcf-file-in-big-query-)
- [Azure Synapse](https://github.com/STRIDES/NIHCloudLabAzure?tab=readme-ov-file#vcf)

### 6. Cloud Platform Fundamentals & Environment Setup
Guides to using Jupyter, VMs, shutdown guards, billing insights, and CSP‑specific tooling.

#### Subtopics
- Jupyter Notebook setup (AWS, Azure, GCP)
- VM usage and auto‑shutdown
- Billing dashboards
- Service-specific beginner workflows

### 7. Specialized & Emerging Topics
Advanced or niche tutorials covering newer research technologies.

#### Subtopics
- Accelerated HPC workflows
- Advanced biomarker discovery
- GenAI‑assisted scientific tooling
- [AI‑enabled visualization pipelines (Azure OpenAI)](https://github.com/STRIDES/NIHCloudLabAzure/blob/main/notebooks/GenAI/notebooks/AI_enabled_visualization.ipynb)

---
## How‑To Docs & Onboarding Aids

Each CSP repository includes practical “how‑to” docs (e.g., notebook environments, auto‑shutdown for VMs/notebooks, billing intros, and environment setup). Start with the **README** in each repo and follow links to the `docs/` folder.

- **AWS:** [STRIDES/NIHCloudLabAWS](https://github.com/STRIDES/NIHCloudLabAWS)
- **Azure:** [STRIDES/NIHCloudLabAzure](https://github.com/STRIDES/NIHCloudLabAzure)
- **Google Cloud:** [STRIDES/NIHCloudLabGCP](https://github.com/STRIDES/NIHCloudLabGCP)

---
## Program Terms & Data Use

- **Credits & Duration:** Up to **$500** for **up to 90 days** (varies by program/use case)
- **Data:** Cloud Lab is for **public/non‑sensitive** data (no PHI/PII)
- **Purpose:** Training, prototyping, benchmarking, and early experimentation — **not** production
- **Terms:** See program terms/conditions in each CSP repo’s `docs/` folder

---
## Support & Next Steps

- **General questions & support:** [STRIDES@nih.gov](mailto:STRIDES@nih.gov)
- **Broader STRIDES information:** [NIH STRIDES Initiative](https://cloud.nih.gov/)
- **Transitioning to long‑term cloud use:** Request a consultation via NIH channels to explore enterprise accounts and options tailored to your data and workload requirements.