# Using VPCs
Pattern: create 'front-end' VPC and one or more 'back-end' VPCs.  Some services require 'specialty VPCs'.  For example, for CloudRun use 'serverless VPC access' and for CloudStorage (GCS) use 'private service access' (see link belows for more info).  

<img src="https://github.com/lynnlangit/gcp-essentials/blob/master/3_networking/3a_VPC%20network/images/vpc-arch.png" width=600>

- Example GCP architecture and best practices for VPC - [link](https://cloud.google.com/vpc/docs/private-services-access#example) see diagram above
- Best practice article "Mitigating Data Exfiltration Risks in GCP using VPC Service Controls" - [link](https://medium.com/google-cloud/mitigating-data-exfiltration-risks-in-gcp-using-vpc-service-controls-part-1-82e2b440197)
- Article: "Using Serverless VPC access" (for CloudRun and more) - [link](https://cloud.google.com/vpc/docs/serverless-vpc-access)
- Article: "Using Private Service Access to connect to VPCs" (for GCS and more) - [link](https://cloud.google.com/vpc/docs/private-service-connect#benefits-apis)