# Ansible Tower Export Documentation

## Description
This is documentation on how to use a the Tower export commands in development. All commands are subject to change.

This command for awx allows you to export all available endpoints for tower for use in import, use in your own templates, for backup and many other uses.

## Installation
clone https://github.com/john-westcott-iv/awx/tree/import-export-collection
cd awxkit
sudo pip3 install -r requirements.txt

## Basic command options
awx export --conf.host https://localhost --conf.username admin --conf.password ******** --conf.insecure --help

awx export --conf.host https://localhost --conf.username admin --conf.password ******** --conf.insecure --job_templates

## Available options for this command
|Option|
|:---:|
|users|
|organizations|
|teams|
|credential_types|
|credentials|
|notification_templates|
|projects|
|inventory|
|inventory_sources|
|job_templates|
|workflow_job_templates|
