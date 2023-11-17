# WIP - Twoge EKS Deployment

## VERY Quick Overview
- Fork/pull source code
- Do Dockerfile magic.
- Fiddle with database creds until something works
- Containerize that lean-mean-webapp-machine and put it on the ol' DockerHub.
    - Well..... Maybe first, make sure everything is good with the configuration using Docker Compose, with an actual database.
- Create all them sweet yaml files for Kubey to gobble up.
- Feed Kubey
    - Test your nommy yamls before giving them to Kubey.
- Deploy to AWS after hours of troubleshooting.
- Rejoice. It is done.(?)


## TODO:
1. Make a real readme
2. Integrate Helm into the mix
3. Learn a bit more about the quotas (yuck)
4. Pin down the most simplistic way of deploying to AWS
5. Create an all-in-one wrapper for all AWS CLI's, and make the stupid commands consistent with one another.
6. Buy a yacht.
