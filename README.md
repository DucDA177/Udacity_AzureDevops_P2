# Overview

Building a CI/CD Pipeline in Udacity Cloud DevOps using Microsoft Azure course

[![Python application test with Github Actions](https://github.com/DucDA177/Udacity_AzureDevops_P2/actions/workflows/main.yml/badge.svg)](https://github.com/DucDA177/Udacity_AzureDevops_P2/actions/workflows/main.yml)

[![Build Status](https://dev.azure.com/duongduc199817/Uda_AzDevops_P2/_apis/build/status/DucDA177.Udacity_AzureDevops_P2?branchName=main)](https://dev.azure.com/duongduc199817/Uda_AzDevops_P2/_build/latest?definitionId=4&branchName=main)

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
 https://trello.com/invite/b/vlUGXGFn/ATTI3d2641551ef880c8b497c92c85454a598F6FEE61/udacityazuredevops
* A link to a spreadsheet that includes the original and final project plan>
https://docs.google.com/spreadsheets/d/1Kq5wYa8EHrp70FqCucyH2pdFH-2tFi41mZW8gNpbV4c/edit?usp=sharing

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>
<p>
<img src="./images/cd-diagram.png" width="100%" />
</p>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service
<p>
<img src="./images/running website.JPG" width="100%" />
</p>

* Project cloned into Azure Cloud Shell
<p>
<img src="./images/clone project.JPG" width="100%" />
</p>

* Passing tests that are displayed after running the `make all` command from the `Makefile` and Output of a test run
<p>
<img src="./images/make all.JPG" width="100%" />
</p>

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

<p>
<img src="./images/azure pipepline build and deploy.JPG" width="100%" />
</p>

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

<p>
<img src="./images/making prediction.JPG" width="100%" />
</p>

* Output of streamed log files from deployed application

<p>
<img src="./images/az webapp log.JPG" width="100%" />
</p>

> 

* Locust load testing chart
<p>
<img src="./images/locust chart.JPG" width="100%" />
</p>

* Locust load testing statics
<p>
<img src="./images/locust report.JPG" width="100%" />
</p>

## Enhancements

<TODO: A short description of how to improve the project in the future>
- UI design 
- Pipeline improvement
- ML model upgrade
## Demo 

<TODO: Add link Screencast on YouTube>
https://www.youtube.com/watch?v=YmLPBLMCxRQ

