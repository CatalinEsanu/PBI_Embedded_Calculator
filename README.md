# PBI_Embedded_Calculator

## Possible configurations
Tenants	- The number of different organization you are going to serve. This is assuming you are going to create different workspaces and different datasets for every tenant.
Reports	- The number of reports per tenant.
Report Elements	- Number of visuals or other elements that affect renders.
Concurrent Report Users	- How many users will consume reports in parallel per tenant.
Report Editors - Number of internal report editors (author once for all tenants).
Shared Tenant Capacity	- Will several tenants use the same Embedded Capacity?
Model Size (MB)	- How large will be your model? (assuming you are using imported datasets and not Direct Query).		
Active Parallel Models Per Tenant - Models that are loaded into memory at the same time.
Parallel Refreshes Per Tenant - Number of datasets that need to be refereshed in parallel.

## Important
There are many factors that may affect your capacity's resource usage. This is tool is supposed to help understand them and give you a general idea of the size and cost of your deployment.
It is always recommended to check your scenario in a POC environment and verify your estimations.