# VPC Module
This module id developed for joindevops company. project inside joindevops inside joindevops follows this module to create their VPC

## Input 
* project (required) - users should specified their project
* environment (required) - users should specified their environment
* cidr_block (optional) - users can provide their CIDR block. Default is 10.0.0.0/16

## outputs
* vpc_id - Exports VPC ID created