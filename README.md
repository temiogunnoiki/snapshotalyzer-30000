# snapshotalyzer-30000
Demo Project to manage AWS EC2 instance snapshots


## About
this project is a demo, that uses boto3 to run EC2 instance snapshots.

## Configuring
shotty uses the configuration file created by the AWS cli e.g.
  `aws configure --profile shotty`

## Running
`pipenv run "python shotty/shotty.py <command> <subcommand>
 <-- project=PROJECT>"`

*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional
