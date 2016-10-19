# Azureml---Publish-web-service-using-R
Microsoft Azure is a cloud computing platform and infrastructure created by Microsoft for building, deploying, and managing applications and services through a global network of Microsoft-managed data centers.
Depending Packages: Xml, Rtools

It gives the option to build machine learning model by importing data sets, write and execute r, python scripts to train and validate models. It also has some inbuilt modules to explore

R has a package AzureML that gives the option to to work with Azure ML Studio datasets and experiments directly from R. Once you create an account with AzureML you get a workspace id and work space authorization code. With these two attributes you could access your cloud based workspace offered in AzureML from R. 
Various things that one can do with AzureML package: 
1)	Upload your datasets to cloud and then analyze
2)	Download the sample datasets
3)	Publish the model as a web service.

Our main focus is on how to publish a model as a web service. The ultimate aim of any model is to sell it and provide it as a service to the client. Once you train and test the model it should be delivered to the client either in the form of an application or as a web service.
