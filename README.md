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

### Log & trace data for anomaly detection of microservice (TrainTicket)
- **Data**: https://fudanselab.github.io/DeepTraLog/; https://github.com/FudanSELab/DeepTraLog
- **Descripiton**: Log and trace data from ICSE '22 paper "DeepTraLog: Trace-Log Combined Microservice Anomaly Detection through Graph-based Deep Learning". It includes log and trace data for nomal and abnormal executions.
- **Data duration**: 
- **Data size**: 
- **Paper**: Chenxi Zhang, Xin Peng, Chaofeng Sha, Ke Zhang, Zhenqing Fu, Xiya Wu, Qingwei Lin, and Dongmei Zhang. "DeepTraLog: Trace-Log Combined Microservice Anomaly Detection through Graph-based Deep Learning." (2022).

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

## 5. Performance data
### Yahoo! Computing System data
- **Data**: https://webscope.sandbox.yahoo.com/catalog.php?datatype=s
- **Description**: Several compputing system monitoring datasets, including a performance metric dataset (33K) an anomaly detection dataset (16M).

### ICPE 2022 Data Challenge dataset
- **Data**: https://icpe2022.spec.org/tracks-and-submissions/data-challenge-track/
- **Description**: The dataset provided by MongoDB includes the performance results from multiple years. It also includes the related data, such as the computed change points, triage decisions, and tickets opened to address the issues.

### ICPE 2023 Data Challenge dataset
- **Data**: https://github.com/SEALABQualityGroup/icpe-data-challenge-jmh
- **Description**: The dataset contains performance measurements of JMH microbenchmarks from 30 Java open source projects.

## 6. Tsinghua Netman Lab AIOps datasets
- **Data**: https://github.com/NetManAIOps
- **Description**: A list of datasets used in publications (e.g., server machine outlier data, KPI anomaly data, hardware failure data).
- **Data size**: varying sizes.
- **Paper**: The associated papers are listed along with the datasets.

## 7. MLOps data
### Microsoft Azure MLOps
- **Data**: https://github.com/microsoft/MLOps
- **Description**: Including code examples of using Azure MLOps pipeline.

### AutoML benchmark
- **Data**:https://github.com/openml/automlbenchmark; 
- **Description**: Benchmarking datasets and code for AutoML.

## 8. Workload traces
### 11 real-world workload traces
- **Data**: Check paper: Kistowski, Jóakim Von, Nikolas Herbst, Samuel Kounev, Henning Groenda, Christian Stier, and Sebastian Lehrig. "Modeling and extracting load intensity profiles." ACM Transactions on Autonomous and Adaptive Systems (TAAS) 11, no. 4 (2017): 1-28.
- **Description**: The paper uses 11 different real-world traces that cover between 2 weeks and 7 months. The paper also describes approaches to extract, model and design workloads. 

## 9. Workload benchmarks (producing your own data)
### HiBench (big data benchmark)
- **Data**: https://github.com/Intel-bigdata/HiBench
- **Description**: HiBench is a big data benchmark suite that helps evaluate different big data frameworks in terms of speed, throughput and system resource utilizations. It contains a set of Hadoop, Spark and streaming workloads, including Sort, WordCount, TeraSort, Repartition, Sleep, SQL, PageRank, Nutch indexing, Bayes, Kmeans, NWeight and enhanced DFSIO, etc. It also contains several streaming workloads for Spark Streaming, Flink, Storm and Gearpump. **The input data size is configurable: available size values are tiny, small, large, huge, gigantic and bigdata**. 

### The DaCapo benchmark
- **Data**: https://dacapobench.sourceforge.net
- **Description**: This benchmark suite is intended as a tool for Java benchmarking by the programming language, memory management and computer architecture communities. It consists of a set of open source, real world applications with non-trivial **memory** loads.

### Workload design methods
- **Paper**: Check paper: Kistowski, Jóakim Von, Nikolas Herbst, Samuel Kounev, Henning Groenda, Christian Stier, and Sebastian Lehrig. "Modeling and extracting load intensity profiles." ACM Transactions on Autonomous and Adaptive Systems (TAAS) 11, no. 4 (2017): 1-28.
- **Descrption**: This paper presents the Descartes Load Intensity Model (DLIM) approach that provides a modeling formalism for describing load intensity variations over time. A DLIM instance is a compact formal description of a load intensity trace. DLIM-based tools provide features for benchmarking, performance, and recorded load intensity trace analysis. The tools can be integrated into simulation contexts and enable benchmarking of elastic or adaptive behavior.

## 10. Other dataset collections
### Google Research datasets
- **Data**: https://research.google/tools/datasets/
- **Description**: A collection of different types of data, such as image, video, audio, text annotation, robotics, cluster traces, DNN hardware acceleration data, etc.

### Stack Overflow/Exchange data related to DevOps
- **Data**: SOTorrent: https://empirical-software.engineering/sotorrent/; Stack Exchange Data Dump: https://archive.org/details/stackexchange.
- **Description**: Questions posted on the SO/SE technique forums may include operations data such as logs, stack traces, etc.

# Contribution
- **Please share other dataset information through pull requests to this repository.**

## Others (please contribute)
