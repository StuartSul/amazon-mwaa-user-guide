# Amazon Managed Workflows for Apache Airflow User Guide

-----
*****Copyright &copy;  Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is Amazon Managed Workflows for Apache Airflow (MWAA)?](what-is-mwaa.md)
+ [Quick start tutorial for Amazon Managed Workflows for Apache Airflow (MWAA)](quick-start.md)
+ [Get started with Amazon Managed Workflows for Apache Airflow (MWAA)](get-started.md)
   + [Create an Amazon S3 bucket for Amazon MWAA](mwaa-s3-bucket.md)
   + [Create the VPC network](vpc-create.md)
   + [Create an Amazon MWAA environment](create-environment.md)
+ [Managing access to an Amazon MWAA environment](manage-access.md)
   + [Amazon MWAA Service-linked role policy](mwaa-slr.md)
   + [Amazon MWAA Execution role](mwaa-create-role.md)
   + [Accessing an Amazon MWAA environment](access-policies.md)
   + [Accessing the Apache Airflow UI](access-airflow-ui.md)
+ [Managing connections to Apache Airflow](manage-connections.md)
   + [Configuring an Apache Airflow connection using a Secrets Manager secret key](connections-secrets-manager.md)
+ [Configuring environments](using-mwaa.md)
   + [Amazon MWAA automatic scaling](mwaa-autoscaling.md)
   + [Amazon MWAA environment class](environment-class.md)
   + [Apache Airflow configuration options](configuring-env-variables.md)
   + [Apache Airflow access modes](configuring-networking.md)
+ [Working with DAGs on Amazon MWAA](working-dags.md)
   + [Adding or updating DAGs](configuring-dag-folder.md)
   + [Installing custom plugins](configuring-dag-import-plugins.md)
   + [Installing Python dependencies](working-dags-dependencies.md)
+ [Networking](networking.md)
   + [About networking on Amazon MWAA](networking-about.md)
   + [Security in your VPC on Amazon MWAA](vpc-security.md)
   + [Managing access to VPC endpoints on Amazon MWAA](vpc-vpe-access.md)
   + [Creating the required VPC service endpoints in an Amazon VPC with private routing](vpc-vpe-create-access.md)
+ [Tutorials](tutorials.md)
   + [Tutorial: Configuring private network access using an AWS Client VPN](tutorials-private-network-vpn-client.md)
   + [Tutorial: Configuring private network access using a Linux Bastion Host](tutorials-private-network-bastion.md)
+ [Code examples for Amazon Managed Workflows for Apache Airflow (MWAA)](sample-code.md)
   + [Using a secret key in AWS Secrets Manager for an Apache Airflow variable](samples-secrets-manager-var.md)
   + [Using a secret key in AWS Secrets Manager for an Apache Airflow connection](samples-secrets-manager.md)
   + [Creating a custom plugin with Oracle](samples-oracle.md)
   + [Creating a custom plugin that generates runtime environment variables](samples-env-variables.md)
   + [Using an AWS CodeArtifact token at runtime](samples-code-artifact.md)
   + [Creating a custom plugin with Apache Hive and Hadoop](samples-hive.md)
   + [Creating a custom plugin for Apache Airflow PythonVirtualenvOperator](samples-virtualenv.md)
   + [Invoking DAGs with an AWS Lambda function](samples-lambda.md)
   + [Invoking DAGs in different Amazon MWAA environments](samples-trigger-dag-envab.xml.md)
   + [Aurora PostgreSQL database cleanup on an Amazon MWAA environment](samples-database-cleanup.md)
   + [Using Amazon MWAA with Amazon RDS Microsoft SQL Server](samples-sql-server.md)
   + [Using Amazon MWAA with Amazon EMR](samples-emr.md)
   + [Using Amazon MWAA with Amazon EKS](mwaa-eks-example.md)
+ [Best practices for Amazon Managed Workflows for Apache Airflow (MWAA)](best-practices.md)
   + [Managing Python dependencies in requirements.txt](best-practices-dependencies.md)
+ [Amazon MWAA metrics](cw-metrics.md)
+ [Amazon Managed Workflows for Apache Airflow service quotas](mwaa-quotas.md)
+ [Security in Amazon Managed Workflows for Apache Airflow](security.md)
   + [Data Protection in Amazon Managed Workflows for Apache Airflow](data-protection.md)
      + [Encryption at Rest](encryption-at-rest.md)
      + [Encryption in Transit](encryption-in-transit.md)
      + [Customer managed CMKs for Data Encryption](custom-keys-certs.md)
   + [AWS Identity and Access Management](security-iam.md)
      + [Troubleshooting Amazon Managed Workflows for Apache Airflow identity and access](security_iam_troubleshoot.md)
      + [How Amazon MWAA works with IAM](security_iam_service-with-iam.md)
   + [Monitoring Amazon Managed Workflows for Apache Airflow](monitoring.md)
   + [Compliance Validation for Amazon Managed Workflows for Apache Airflow](compliance-validation.md)
   + [Resilience in Amazon Managed Workflows for Apache Airflow](disaster-recovery-resiliency.md)
   + [Infrastructure Security in Amazon MWAA](infrastructure-security.md)
   + [Configuration and Vulnerability Analysis in Amazon MWAA](w445aac33c32.md)
   + [Best practices](security-best-practices.md)
+ [Amazon MWAA API actions and resources](mwaa-actions-resources.md)
+ [Amazon MWAA frequently asked questions](mwaa-faqs.md)
+ [Troubleshooting Amazon Managed Workflows for Apache Airflow (MWAA)](troubleshooting.md)
+ [Amazon MWAA Document History](doc-history.md)