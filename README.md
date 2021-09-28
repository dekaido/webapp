## Project Title - Deploy a high-availability web app using CloudFormation
This repo provides the code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. 

### Note to run:
Example to update stack:

			dekaido@penguin:~/udacity/webapp/bash$ bash update.sh udagram ../scripts/infrastructure.yml ../scripts/parameters.json

Result:
			{
				"StackId": "arn:aws:cloudformation:us-west-2:835758441568:stack/udagram/be5749a0-2065-11ec-a19c-0642c62a6a49"
			}

### This folder contains the following files:
**Scripts for:**
- iam roles
- network
- server

**Parameters for:**
- network
- server

**Commands for:**
- create stack
- update stack
- delete stack
- deploy Sample UserData
	*When creating your Launch Configuration, you may need a UserData script*
	*here's one that you can use for Ubuntu Linux that will:*
	*Install Apache Web Server, Start it, and create an index.html that will be displayed*
	*when you visit the IP address of this server with your web browser*