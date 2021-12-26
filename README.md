# Operationalizing Machine Learning

## Overview

In this project an AutoML model is created, deployed and consumed via Rest API. 
Then the process is auromated using a pipeline. Finally, the pipeline is published and accessed via Rest API. The steps are:

1) Authentication
2) Automated ML Experiment
3) Deploy the best model
4) Enable logging
5) Swagger Documentation
6) Consume model endpoints
7) Create and publish a pipeline
8) Documentation

## Architectural Diagram

<img src="img/arch-diagram.png" alt="Architectural Diagram"/>

- Authentication is vital to allow third party applications to securely use your published APIs.
- AutoML Model allows to search the best model for you within a time frame. 
- Deploy the best model will allow the model to be available via API using the ACI and enable Auth. 
- Enable Logging will allow you to see any error message during/after the deploy.
- Consume model enpoints will allow the model to make a prediction via Rest API.
- Create and publish a pipeline make the trained model available via rest api and provides a way to interact with the pipeline.
- Documentation: the API methods are documented using swagger. 


## Steps

### Deploy model in Azure ML Studio
1. Dataset uploaded

<img src="screenshots/1.png"/>

2. AutoML model completed

<img src="screenshots/2.png"/>

3. Enable Applications insights

<img src="screenshots/3.png"/>

4. Enable Logging

<img src="screenshots/4.png"/>

5. Swagger doc

<img src="screenshots/5.png"/>

6. Consume API

<img src="screenshots/6.png"/>

## Publish an ML Pipeline

1. Pipeline and its endpoint

<img src="screenshots/7.png"/>

2. Published pipeline overview

<img src="screenshots/8.png"/>

3. Pipeline steps

<img src="screenshots/9.png"/>

4. Experiments including scheduled pipelines
<img src="screenshots/10.png"/>


# Screencast

Link: https://youtu.be/Ggy56Y8pTgY


