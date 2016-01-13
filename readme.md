
# Azure Resource Naming
The following guide is completely subjective, and should be considered strictly a reference and not gospel.
All naming is suggested to be Pascal case. {-ENV} can be added to any of the resources to identify the environment that the resource lies (i.e.: '-DEV' , '-QA').


## Resource Groups
##### Suggestion for naming : {Application-RG}
A resource group is the top level container that holds a collection of items. They are relative to whatever the consumer wants. Could be application related, data reated, or both.
If using ARM, you can add tags as descriptors, for internal use and billing.

## Cloud Services
##### Suggestion for naming : {Application-CS}
This is for web roles and worker roles. CS could be swapped for WORK or WEB as this might be more declarative for web and worker roles.

## Storage Accounts
##### Suggestion for naming : {Application-ST}
This is for Storage Accounts. Used for Blob, Table and Queues. Also hold vm images. 

## Virtual Machines
##### Suggestion for naming : {Application-[TYPE]-VM}
This is for virtual machines. [TYPE] is optional and would signify SQL, LINUX, IIS, etc.  
