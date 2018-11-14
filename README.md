---
topic: sample
languages:
- csharp
- fsharp
- vbnet
technologies:
- office
- windows
- xbox
name: 'My amazing sample'
urlFragment: my-amazing-sample
description: 'I probably would have put an amazing description here as well.'
statusNotificationTargets:
- dendeli@microsoft.com
azureDeploy: https://azuretemplate.bing.com/deployments/deploy.json
extendedZipContent:
- path: ../../media/header.png
  target: /pictures
extensions:
- officeDevId: 3bb16609-f17e-4f5c-8a01-16db13c7c98c
ci:
- path: /fx
  template: dotnet_fx_3.5
- path: /core/sample1
  template: dotnet_core_2.0
- path: /core/sample2
  template: dotnet_core_1.1
- path: /core/sample3
  dockerfile: ../../Dockerfile
  dockerPlatform: linux
---

# Model in Azure AI Gallery

## Intro
This repository contains code which demonstrates how to deploy and use an Inception model in Azure Machine Learning. Try it today with Azure Notebooks.

## How to Use
1. Use [![Azure Notebooks](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/gogowings/Your_Gallery_Repo) to [import the sample notebooks](https://notebooks.azure.com/import/gh/gogowings/Your_Gallery_Repo) into Azure Notebooks.
2. Run the [configuration notebook](Notebooks\00.configuration.ipynb) to create your workspace.
3. Run the [deployment notebook](Notebooks\01.deployment.ipynb) to create your workspace.
4. Run the [brainwave notebook](Notebooks\02.brainwave-quickstart.ipynb) to create your workspace. 

# Resources


## About Azure ML
Get the full documentation for Azure Machine Learning service at https://docs.microsoft.com/azure/machine-learning/service/

## More Examples
 * [Azure/MachineLearningNotebooks GitHub site](https://github.com/Azure/MachineLearningNotebooks)
