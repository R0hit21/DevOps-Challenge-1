This folder contains the following challenge

Challenge #2

We need to write code that will query the meta data of an instance within AWS and provide a json formatted output. 


To do challenge 2:
1. i have created a virutal machine  on azure.
2. intalled jq on ubuntu.
3. used below command to get metadata 
curl -s -H Metadata:true --noproxy "*" "http://169.254.169.254/metadata/instance?api-version=2021-02-01" | jq





