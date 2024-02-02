# Introduction 
**You can click the button below to download the project:**
[<img src="https://i.imgur.com/Nkja8PR.png" alt="Download from Google Drive" style="width: 128px; height: 32px;">](https://drive.google.com/drive/folders/16EyKaGnn3eb-FftpjSQLzRr9PReT1TZk?usp=drive_link)

**More datasets**
Due to the limit of google drive space. Here you can find additional archives (Dec 2019 - Apr 2020) and put them into your `data` folder. The links are here:

- [2019-Oct.csv.gz](https://data.rees46.com/datasets/marketplace/2019-Oct.csv.gz) (1.62Gb)
- [2019-Nov.csv.gz](https://data.rees46.com/datasets/marketplace/2019-Nov.csv.gz) (2.69Gb)
- [2019-Dec.csv.gz](https://data.rees46.com/datasets/marketplace/2019-Dec.csv.gz) (2.74Gb)
- [2020-Jan.csv.gz](https://data.rees46.com/datasets/marketplace/2020-Jan.csv.gz) (2.23Gb)
- [2020-Feb.csv.gz](https://data.rees46.com/datasets/marketplace/2020-Feb.csv.gz) (2.19Gb)
- [2020-Mar.csv.gz](https://data.rees46.com/datasets/marketplace/2020-Mar.csv.gz) (2.25Gb)
- [2020-Apr.csv.gz](https://data.rees46.com/datasets/marketplace/2020-Apr.csv.gz) (2.73Gb)

**Our teammembers are:**
- Yi-Hsuan Hung (Shannon)
- Ya-Hsien Kuo (Clara)	
- Nikolai Rekow 

# Environment 
- Python above 3.8.0 or 3.12.0 
- Pyspark 3.5.0

# Getting Start
- `data`: The folder contains all the data used in the project.
- `.code/1-Scaling-Observation.ipynb`: The jupyter notebook for testing the scaling of the data.
  - Testing with 7 files that the amount of data increases in the orders of magnitude (1x/10x/100x/1000x/10000x/200000x/1000000x)
  - Testing with 5 types of different hardware configurations
- `.code/2-Fault-Tolerance.ipynb`: The jupyter notebook for testing the fault tolerance of the data.
  - Creating a cluster with 3 nodes. 
  - Testing with killing the java process of one of the nodes.
  - See if the cluster can still work and how the spark cluster handle the fault and achieve the fault tolerance. 
- `.code/3-RFM-Segmentation.ipynb`: The jupyter notebook for testing the RFM segmentation of the data.
  - Solving the Big Data usecase for RFM
  - Scaling the data based on standalone cluster
  - Changing cluster configuration to observe how it affects the resources and performance

```bash 
.
├── data # all the data used in the project 
└── code
    ├── 1-Scaling-Observation.ipynb
    ├── 2-Fault-Tolerance.ipynb
    ├── 3-RFM-Segmentation.ipynb
    └── README.md
```


