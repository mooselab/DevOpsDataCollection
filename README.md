# DevOps Data Collection
A collection of DevOps datasets that aim to facilitate research and development to support DevOps intelligence.

## 1. Large-scale cloud trace data
### Google cluster workload traces
- **Data**: https://github.com/google/cluster-data
- **Description**: Traces of the workloads running on Google Borg compute clusters. The trace describes every job submission, scheduling decision, and resource usage data for the jobs that ran in those clusters. There are two versions of the data:  one trace for the month of May 2011 and another for May 2019.
- **Data duration**: 29 days (2011 version); 29 days (2019 version).
- **Data size**: 41 GB compressed (2011 version); 2.4TiB compressed (2019 version).
- **Papers built on the dataset**: https://github.com/google/cluster-data/blob/master/bibliography.bib

### Alibaba cluster trace data
- **Data**: https://github.com/alibaba/clusterdata
- **Description**: Trace datasets collected from thousands of machines in Alibaba clusters.
- **Data duration**: The latest dataset covers 2 months of data from 6500 machines.
- **New traces**: GPU trace data 2020 covers 2 months of data; Microservice trace data 2021 covers 12 hours of data.
- **Data size**: Varying sizes.
- **Papers**: listed in the data repo.

### Microsoft Azure trace data
- **Data**: https://github.com/Azure/AzurePublicDataset
- **Description**: This repository contains four public datasets of Microsoft Azure traces (VM traces, function traces) for the benefit of the research and academic community.
- **Data duration**: Varying durations (check the description of the respect dataset page).
- **Data size**: Varying sizes (check the description of the respect dataset page).
- **Papers**: "Resource Central: Understanding and Predicting Workloads for Improved Resource Management in Large Cloud Platforms", SOSP’17.

## 2. Application and system logs

### Loghub 
- **Description**: A large collection of system and application logs, provided by the LogPAI team. Some datasets (e.g., HDFS, BGL logs) include normal/abnormal labels.
- **Data**: GitHub (descriptions and sample data): https://github.com/logpai/loghub; Zenodo (complete data): https://zenodo.org/record/3227177#.YPBSly297T8
- **Paper**: He, Shilin, Jieming Zhu, Pinjia He, and Michael R. Lyu. "Loghub: A large collection of system log datasets towards automated log analytics." arXiv preprint arXiv:2008.06448 (2020).

### OpenStack failure dataset (error logs produced by the OpenStack Cloud Computing platform)
- **Data**: https://figshare.com/articles/dataset/Failure_dataset/7732268/2
- **Description**: This failure dataset contains the injected faults, the workload, the effects of failure (both the user-side impact and our own in-depth correctness checks), and the error logs produced by the OpenStack cloud management system.
- **Data size**: 216 MB compressed.
- **Paper**: Cotroneo, D., De Simone, L., Liguori, P., Natella, R., & Bidokhti, N. (2019, August). How bad can a bug get? an empirical analysis of software failures in the openstack cloud computing platform. ESEC/FSE '19.

### SecRepo's Security related log datasets
- **Data**: http://www.secrepo.com
- **Descrption**: A list of security log datasets such as malware and system/access logs.
- **Data size**: varying sizes.

### VizSec security log datasets
- **Data**: https://vizsec.org/data/
- **Description**: including a number of security-related log datasets.
- **Data size**: varying sizes.

### EDGAR's Apache access log data
- **Data**: https://www.sec.gov/dera/data/edgar-log-file-data-set.html
- **Descrption**: The Division of Economic and Risk Analysis (DERA) has assembled information on internet search traffic for EDGAR filings through SEC.gov generally covering the period February 14, 2003 through June 30, 2017. The EDGAR Log File Data Set contains information in CSV format extracted from Apache log files that record and store user access statistics for the SEC.gov website.
- **Data duration**: 2003 to 2017.
- **Data size**: multiple files.

## 3. Computer/cluster/cloud failure data
### The Computer Failure Data Repository (CFDR)
- **Data**: https://www.usenix.org/cfdr
- **Description**: A list of computer/cluster failure datasets, including hadware failure/replacement data, node outage data, event/error logs. The computer failure data repository (CFDR) aims at accelerating research on system reliability by filling the nearly empty collection of public data with detailed failure data from a variety of large production systems.
- **Data size**: varying (wide-range) sizes.
- **Paper**: Some papers using the data can be found at: https://www.usenix.org/cfdr-data

## 4. Disk failure data
### Backblaze disk failure dataset
- **Data**: https://www.backblaze.com/b2/hard-drive-test-data.html
- **Description**: Disk status data collected from tens of thousands of hard disks monitored over years with daily granularity.
- **Data duration**: from 2013 to 2021 (continuing)
- **Data size**: several GBs of data per year.
- **Paper**: Several papers, including: "Proactive error prediction to improve storage system reliability." USENIX ATC '17.


## 5. Tsinghua Netman Lab AIOps datasets
- **Data**: https://github.com/NetManAIOps
- **Description**: A list of datasets used in publications (e.g., server machine outlier data, KPI anomaly data, hardware failure data).
- **Data size**: varying sizes.
- **Paper**: The associated papers are listed along with the datasets.

## 6. Stack Overflow/Exchange data related to DevOps
- **Data**: SOTorrent: https://empirical-software.engineering/sotorrent/; Stack Exchange Data Dump: https://archive.org/details/stackexchange.
- **Description**: Questions posted on the SO/SE technique forums may include operations data such as logs, stack traces, etc.

## 7. MLOps data
### Microsoft Azure MLOps
- **Data**: https://github.com/microsoft/MLOps
- **Description**: Including code examples of using Azure MLOps pipeline.

### AutoML benchmark
- **Data**:https://github.com/openml/automlbenchmark; 
- **Description**: Benchmarking datasets and code for AutoML.

### Yahoo! Computing System data
- **Data**: https://webscope.sandbox.yahoo.com/catalog.php?datatype=s
- **Description**: Several compputing system monitoring datasets, including a performance metric dataset (33K) an anomaly detection dataset (16M).

## Contribution
- **Please share other dataset information through pull requests to this repository.**
