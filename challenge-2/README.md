# Challenge-2

## AWS Metadata Challenge

## Purpose
- Query the metadata of an ec2 instance within AWS and provide a json formatted output.
- Retrieve the value of a particular data key.

## Prerequisites
- Create an EC2 Linux instance on AWS
- SSH into the instance
- Install Python 3 and git on your instance
    - `sudo yum install python3 git`
- Install pipenv
  - `sudo pip3 install pipenv`
- Clone  repository
- Open the repository on your instance
  - `cd challenge-2`
- Install project dependancies
  - `pipenv install`


## Usage
- Open the `src` folder
  - `cd challenge-2/src`
- Run whichever script you need:
  - `python3 get_complete_metadata.py`
  - `python3 get_key.py`
