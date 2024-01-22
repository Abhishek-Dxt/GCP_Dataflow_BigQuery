# Streaming data to BigQuery using Dataflow Pipeline and performing analytics on Looker Studio

This is a Qwiklabs cloud project, where I will be creating a **data pipeline on Google Cloud Platform or GCP**. 
The pipeline will stream real time data from **Cloud Storage to BigQuery using Dataflow**.
Data analysis can later be done on **BigQuery** using standard SQL queries, or with the help of visualizations on **Looker Studio**.

## Creating an empty BigQuery dataset and schema to stream into later - 
<img width="935" alt="0" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/f992f3b9-ff5d-4ce0-aa81-1df9e1dca2d9">

## Moving files from Cloud Storage for the Dataflow job (data is present in a cloud storage bucket) -
<img width="941" alt="1" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/bbac4d56-7e05-49df-b748-cdc4935c4ab7">

## Building a Dataflow pipeline to read files from the Cloud Storage Bucket and write data to BigQuery. 
#### Creating a Dataflow job from template - Cloud Storage Text to BigQuery (Stream)


<img width="872" alt="3" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/cb5a1eb3-d743-496d-a376-53f644142c2b">

#### Then I will describe the source and sink of the pipeline - 


<img width="566" alt="4" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/06a0a74e-c303-4f6c-887b-b037c28d6011">

#### Streaming Job has started - 


<img width="670" alt="5" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/5f30b55f-6cd4-4acd-8f3c-53a070775479">

## Querying the streaming data on BigQuery - 
<img width="696" alt="6" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/5e5c2b4a-597d-47be-846f-36d58573040d">

## Analyzing Data on Looker Studio (which comes integrated with BigQuery) - 
<img width="897" alt="7" src="https://github.com/Abhishek-Dxt/GCP_Dataflow_BigQuery/assets/71979171/b5dbeb69-5c77-4816-9074-a321f72e44e1">
