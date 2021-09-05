
#############################################
# Setup Instructions: network/setup/README.md
#############################################

1. Initialize the Dev invironment
> dev-init.sh   -flag  -flag

# Validate dev environment
> dev-validate.sh

To get help
> dev-init.sh -h

2. Explorer
- Start with the environment use the -e flag
> dev-init.sh -e
> exp-stop.sh

- At a later time
> exp-start.sh
> exp-stop.sh

3. Environment scripts

- Set the org context
>  .   set-env.sh    acme | budget

- To check current environment
> show-env.sh

4. Chaincode operations
- Set the chaincode environment
> set-chain-env.sh  -flag ..  -flag ..

- To check current chaincode parameters
> show-chain-env.sh   


