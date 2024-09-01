# Innovation Hack PriceAI Solution

This is the framework to get, clean, process data and generate models. It is also available with a backend Flask API and UI interface for UX.

![demoImg](https://github.com/user-attachments/assets/e4b93ad6-ab4d-4b75-93be-52834a6ca8a3)

Demo - https://hs95.pythonanywhere.com/

## Details

Problem: Predicting accurate shipping cost a shipper would need to pay for logistics.

Objective: A comprehensive model which can predict and forecast shipping costs based on real data with parameters ranging from shipment details, geographical data, economic factors

Solution - PriceAI

An AI model which can predict pricing for shipment considering quantitative data variables and indicators using real world datasets. It is a framework for building models for logistics along with working model to predict shipping cost for domestic shipping and an interactive interface

Features:

The product leverages machine learning for prediction and forecasting depending on various key features and markers in logistics and shipping.
A user interface platform is provided to analyze, along with APIs for quick integration to real world enterprise products
The solution is end to end prototype with capability of feeding various dataset and generating regression models based on parameters to predict cost
The solution is trained on real world dataset with multiple factors and can be easily scaled up for different markets and datasets.


Prototype Demo Code with pickled model - https://github.com/hsb4995/pred-demo-webapp

## Run Locally

These instructions for are on how to run the notebooks, for running application locally please follow details at - https://github.com/hsb4995/pred-demo-webapp/blob/main/README.md

Clone the project

```bash
  [git clone https://github.com/hsb4995/pred-demo-webapp.git](https://github.com/hsb4995/PriceAIEDA.git)
```

Unzip the dataset, zipped it due to size being large


Open notebook such as minPrice1SepNotebook or CourierDataModeldtdc_30_aug in jupyter

Run all cells 

## Project Structure

1. archiveData - Data that was intermediate to generate, fetch, consolidate datasets along with temp files
2. archiveEDA - EDA analysis which were done to generate consolidated pincodes with lat, long, understanding of features etc
3. DataGen - Contains datasets
4. demoApp - This is the Flask application with interface which takes model and is hosted on cloud. It is managed on a seperate git repo as well
5. models - dumps of models generated while doing EDA
    
