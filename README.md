#  Azure Security Score
## 1. Introduction
### 1.1	Overview



## 2 Logical Architecture
### 2.1	Logical System Component Overview
![Figure 2: Logical Architecture Overview](./images/workflow.png)
- 2 tables get pulled from Azure Security Center and Azure REST API to AWS Sagemaker Studio lab for EDA.
![Firegure 2.1: Azure Security Center](images/securitycenter.png)
![Firegure 2.2: Azure REST API](images/api.png)

- Data wraggling to be performed via Jupyter lab to feed data to Power BI.
![Firegure 2.3: Jupyterlab](images/sagemaker.png)

- Notebook gets pushed to github repo.
![Firegure 2.4: Github](images/github.png)

- Power BI report gets built with the ingested data.
![Figure 2.5: Power BI Dashboard](./images/powerbi.png)

- The end users can consume the BI report.

## 3 Power BI report Link
Ref: [Power BI Report Link](./images/powerbi.pdf)

## 4 MS Docs Link
Ref: [MS Docs: Azure REST API](https://learn.microsoft.com/en-us/rest/api/managementgroups/)

