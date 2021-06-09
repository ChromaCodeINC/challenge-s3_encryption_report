### Bucket Encryption Reporting

In an effort to demonstrate the ability to develop real-world automated tasks,  
we'd like you to address the following scenario:   
  
An audit has determined we must enforce encryption on all S3 buckets in our AWS  
account.  To facilitate compliance, we must be able to identify buckets which do  
not comply on an on-going basis.  Provide a tool that will give us a report of  
buckets which are not in compliance with the 'Enforce Encryption' policy.  You are  
expected to provide a reasonable amount of resiliency and error handling/reporting  
as part of the solution.
  
It is expected that you will use either `python/boto3` or `bash/jq` as the basis for  
your solution.  You can assume the AWS profile information (API key, region, etc) is  
already provided to the environment, but it's your responsibility to verify that or  
handle accordingly.  As a final step, please provide a `Dockerfile` to produce a  
minimal image which runs your report.  
  
Submit your solution by creating a pull-request targeted at the branch containing  
this README.
