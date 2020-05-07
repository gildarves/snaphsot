# Snapshot

Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo and uses boto3 to manage AWS ECE instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py` <command> <subcommand>
<--project-PROJECT>"

*command* is list,start, or stop
*subcommand* - depends on command
project is optional
