### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack network.yml network-parameters.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.sh mySecStack servers.yml server-parameters.json
```
```command line bat
./create.bat myFirstStack network.yml network-parameters.json
./create.bat mySecStack servers.yml server-parameters.json
# Delete stack
./delete.bat mySecStack
```