# awsinstance-docker-jenkins
Test Instance to deploy network, instance and jenkins in a container

## Network | Server | Route

**Run the script _instance.yml_ to deploy the environment**
`./create.bat demoinst instance.yml instance-params.json`

### The infrastructure deployed is with a public VPC with a single Public Subnet**
**This instance is lunched with aws, unzip, docker, and git installed**

_Subsequent update would have the instance.yml install and deploy the container automagically, this would be achieved by doing git clone in the lunchconfig_

## Jenkins docker build on the deployment above
_make script.sh executable_
`chmod +x script.sh`

_docker build for jenkins while setting the environment var_
`./script.sh`




