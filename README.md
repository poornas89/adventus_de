# Data Engineer / BigQuery & Python Challenge


## overview
First, I had to do is set up a python virtual environment. I'm familiar with Anaconda and I used it for this exercise. Then I had to setting up a service account and download the private key. I kept it in my PC and setup the ‘GOOGLE_APPLICATION_CREDENTIALS’ parameter within the project scope. 
This is the first time I’m using Bigquery so I decided to use a Jupyter notebook because it’s really easy to use. 
When loading the fist file I define some columns as mode=”REQUIRED”. But when loading the second file I had to change all the columns to NULLABLE. It is mandatory to change columns mode as nullable to enable auto update the schema. 
For Streaming insert the customers_3.json file, had to do two changes. 
 1) Set ignore_unknown_values to Ture. So, this will ignore new columns which available in steaming dataset. 
 2) The column named “Balance” automatically converted to float when loading the second file. But before loading the 3rd file I had to remove the "$" sign and the comma manually from that column. 
 Without these two changes steaming loading did not work. 
 
 ## How to run the project locally
1) Create a python virtual environment. Install bigquery libraries. 
2) Set up a service account and download the private key.
3) Change path mentioned in “creadentials_path” variable to your private key location.
4) Change the “table_id” variable. (format – Your_project_name.Your_dataset_name.Table_name)
