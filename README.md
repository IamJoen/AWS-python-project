# AWS-python-project
Manage EC2 instance snapshots via Python

Script is saved in shotty/shotty.py

## Use the following command after saving the Script
pipenv run python shotty/shotty.py

##Use the following to list the instances for a specific project tag (Delta for eg.)/all
pipenv run python shotty/shotty.py list --project="Delta"
pipenv run python shotty/shotty.py list


##Use the following to start the instances for a specific project tag(Delta for eg.)/all
pipenv run python shotty/shotty.py start --project="Delta"
pipenv run python shotty/shotty.py start

##Use the following to stop the instances for a specific project tag(Delta for eg.)/all
pipenv run python shotty/shotty.py stop --project="Delta"
pipenv run python shotty/shotty.py stop

##Use the following to seek help for specific action
pipenv run python shotty/shotty.py start --help
pipenv run python shotty/shotty.py stop  --help
pipenv run python shotty/shotty.py list  --help
