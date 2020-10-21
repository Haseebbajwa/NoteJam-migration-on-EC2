# NoteJam-migration-on-EC2
New Architect for Notejam app on AWS
This repository contains an example of infrastructure for on-premise application which is going to be deployed in AWS public cloud The application itself can be found in the git repo https://github.com/nordcloud/notejam

# Notejam application stack
Provision: CloudFormation
CI/CD: CodePipeline/CloudBuild with CodeCommit integration
App: EC2 Instances
Database: RDS (mysql)
Monitoring: Cloudwatch
Logs: Cloudwatch for app logs as well as S3.

# Execution:
Execute CloudFormation templates located in Deployment folder. Please note that you also need to specify all parameters when deploying.

architecture can be found in the Architecture folder in this repo.
