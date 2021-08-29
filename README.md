# DevOpsDataCollection
A collection of DevOps datasets that aim to facilitate research and development to support DevOps intelligence.

## Large-scale cloud trace data
### Google cluster workload traces
- **Data**: https://github.com/google/cluster-data
- **Description**: Traces of the workloads running on Google Borg compute clusters. The trace describes every job submission, scheduling decision, and resource usage data for the jobs that ran in those clusters. There are two versions of the data:  one trace for the month of May 2011 and another for May 2019.
- **Data duration**: 29 days (2011 version); 29 days (2019 version).
- **Data size**: 41 GB compressed (2011 version); 2.4TiB compressed (2019 version).
- **Papers built on the dataset**: https://github.com/google/cluster-data/blob/master/bibliography.bib

### Microsoft Azure trace data

## Application and system logs

### Loghub (a large collection of system and application logs, provided by the LogPAI team)
- **Data**: GitHub (descriptions and sample data): https://github.com/logpai/loghub; Zenodo (complete data): https://zenodo.org/record/3227177#.YPBSly297T8
- **Paper**: He, Shilin, Jieming Zhu, Pinjia He, and Michael R. Lyu. "Loghub: A large collection of system log datasets towards automated log analytics." arXiv preprint arXiv:2008.06448 (2020).

### OpenStack failure dataset (error logs produced by the OpenStack Cloud Computing platform)
- **Data**: https://figshare.com/articles/dataset/Failure_dataset/7732268/2
- **Description**: This failure dataset contains the injected faults, the workload, the effects of failure (both the user-side impact and our own in-depth correctness checks), and the error logs produced by the OpenStack cloud management system.
- **Data size**: 216 MB compressed.
- **Paper**: Cotroneo, D., De Simone, L., Liguori, P., Natella, R., & Bidokhti, N. (2019, August). How bad can a bug get? an empirical analysis of software failures in the openstack cloud computing platform. ESEC/FSE '19.

### A list of security related log datasets
- **Data**: http://www.secrepo.com
- **Descrption**: A list of security log datasets such as malware and system/access logs.
- **Data size** varying sizes.

## Computer/cluster/cloud failure data
### The Computer Failure Data Repository (CFDR)
- **Data**: https://www.usenix.org/cfdr
- **Description**: A list of computer/cluster failure datasets, including hadware failure/replacement data, node outage data, event/error logs. The computer failure data repository (CFDR) aims at accelerating research on system reliability by filling the nearly empty collection of public data with detailed failure data from a variety of large production systems.
- **Data size**: varying (wide-range) sizes.
- **Paper**: Some papers using the data can be found at: https://www.usenix.org/cfdr-data

## Disk failure data

## Metrics & Alerts

## Other data
