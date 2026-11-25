# CLAUDE.md
## Project
What this project is for and about

## Hard rules
All AWS resources go in region eu-west-2
Instances are reached through ssm manager and port 22 is never opened
IAM policies grant only permissions that are required based on needs of the services
Secrets never go in repo
After every session, run destory everything  and confirm nothing is left running

## Workflow
always create a feature branch and pull a merge request to push it to the main

## Don'ts
Never commit files (look at your .gitignore)
Never push directly to main
