# Udagram Project - Udacity Nanodegree
Udacity Udagram Project - second project for the Udacity Nanodegree Cloud DevOps Engineer Nanodegree Program.

## Step 1
Run network.yml
`aws cloudformation create-stack --stack-name network --template-body file://network.yml --parameters file://network-params.json --capabilities CAPABILITY_IAM`

## Step 2
Run bastion-server.yml
`aws cloudformation create-stack --stack-name servers --template-body file://servers.yml --parameters file://servers-params.json --capabilities CAPABILITY_IAM`

