# Monitoring Tool: Trace

### Team Members
* Shruti Kuber(skuber)
* Rounaq Saxena
* Deepak Nair
* Phaniprakash

### About the Tool

Trace is an open source performance monitoring and error detection tool used for Nodejs applications. It is best suited for microservices based architectures. Taking inspiration from Google Dapper, trace addresses common issues developers face when scaling out their microservices — transaction tracking, monitoring, alerts, and infrastructure visualization. The visualization tools provided by Trace help developers to easily identify the issues in the application and the parts of the application they are arrising from.

### Features

#### Topology View
One of the most important features of this tool, this view helps us to visualize the different services in the application and how they communicate with each other. These services can be databases and 3rd party API's. Each service can be individually monitored and their throughput and response times can be recorded.

#### Trace View
This view gathers information of the various transaction requests in the application and all the transactions with errors are displayed on this view. It helps to easily spot what the errors were in a transaction, where they occurred, check the timings (*) and what other services it affected.
