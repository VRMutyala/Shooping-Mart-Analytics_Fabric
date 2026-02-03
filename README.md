**Project Overview**

This project was designed and implemented using Microsoft Fabric, leveraging both structured and unstructured sample data. The solution follows the Medallion Architecture approach to ensure scalable, organized, and high-quality data processing.

**Architecture Flow**

1.	Data Ingestion - API (Structured and Unstructured)
2.	Bronze Layer – Raw data storage
3.	Initial Processing – Basic validation and standardization
4.	Silver Layer – Cleaned and transformed data
5.	Further Processing – Business logic and enrichment
6.	Gold Layer – Analytics-ready, curated data
7.	Data Visualization – Insights and reporting
   
**Technologies & Components Used**

1.	APIs
2.	Lakehouse (Delta tables)
3.	Notebooks (PySpark)
4.	Pipelines
5.	Dataflow Gen2
6.	Power BI

**Note** : Due to Microsoft Fabric security and authentication policies, the workspace cannot be made public. This repository documents the complete architecture, implementation approach, and outputs using screenshots and sample code.

**List View Task Creation - Medallion Architecture**
<img width="1918" height="863" alt="image" src="https://github.com/user-attachments/assets/9a550e3f-93c8-4872-8f6b-d35787f9a2d0" />

**Lineage View**
<img width="1913" height="858" alt="image" src="https://github.com/user-attachments/assets/270aa50c-8e67-4e73-bdc7-92389b698efa" />

**Ingest Structured data from API to Bronze Layer (Dynamic Pipeline)**
<img width="1811" height="802" alt="image" src="https://github.com/user-attachments/assets/f253b9be-5d78-4250-aea3-1d48dbc1d0a6" />

**Ingest UnStructured data from API to Bronze Layer (Dynamic Pipeline)**
<img width="1825" height="792" alt="image" src="https://github.com/user-attachments/assets/6009d382-93b6-4b99-be57-90eb51a9434e" />

**Bronze Layer (Lakehouse)**
<img width="1912" height="598" alt="image" src="https://github.com/user-attachments/assets/a47e268d-7700-4600-815e-ef63ebe195c2" />

**Bronze Layer (Notbook - Raw Data)**
<img width="1906" height="763" alt="image" src="https://github.com/user-attachments/assets/4fdd4a6c-903a-4d1f-b243-0296e3c7316e" />

**Silver Layer (Lakehouse)**
<img width="1822" height="805" alt="image" src="https://github.com/user-attachments/assets/d15b2169-f1eb-47ed-956a-11e7eadfcc1e" />

**Silver Layer (Notbook - Cleansing Data)**
<img width="1820" height="763" alt="image" src="https://github.com/user-attachments/assets/ecbc142c-15ed-4281-964c-5d0358e6fc44" />

**Gold Layer (Lakehouse)**
<img width="1817" height="796" alt="image" src="https://github.com/user-attachments/assets/9428232e-287b-4b3d-a40a-6d5c6913a9de" />

**Gold Layer (Notbook - Aggregrations & Transformations)**
<img width="1806" height="757" alt="image" src="https://github.com/user-attachments/assets/cee77dfb-6d0e-4091-b0b7-b09215fa3aa6" />

**Semantic Model**
<img width="1807" height="798" alt="image" src="https://github.com/user-attachments/assets/1abc3d21-ccfb-4573-9c54-ac871ad3eb0d" />

**Visulizations**
<img width="1275" height="712" alt="image" src="https://github.com/user-attachments/assets/065e7856-ebce-4972-b0a3-bcc02a730653" />
<img width="1273" height="710" alt="image" src="https://github.com/user-attachments/assets/9450fb7d-d0f2-4528-ad30-87c576bfa235" />


