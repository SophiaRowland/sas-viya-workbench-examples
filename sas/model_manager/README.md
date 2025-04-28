# SAS MODEL MANAGER INTEGRATION EXAMPLES IN SAS <!-- omit in toc -->

## Overview

This repository contains examples of connecting to SAS® Viya and registering models to SAS® Model Manager® in SAS.

## Prerequisites
The examples in this folder require access to a SAS® Viya® Workbench and SAS Model Manager on SAS Viya. These examples also require an access token for SAS Viya, which you can generate using [Authentication Example Notebook](authentication_example.sasnb) and save in the [myToken file](myToken.sas). 


## Authenticate to SAS Viya

Generate an access token for SAS Viya. 
[notebook](authentication_example.sasnb)

## Save Access Token

Save access token for use in model registration
[program](myToken.sas)

## Simple Registration Example

Register a logistic regression and decision tree trained on the hmeq data set.
[notebook](hmeq_example.sasnb)

## More Complex Registration Example

Register a logistic regression and gradient boosting model trained on the adult data set.
[notebook](salary_example.sasnb)

For implementation steps and usage instructions, refer to the code files.
