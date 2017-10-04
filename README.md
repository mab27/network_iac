# NW Infrastructure-As-Code

## Network IaC definition:

- Network IaC means you are treating your network devices configurations in a manner similar to source code. This includes following software development practices for testing and deploying these changes to production: version control, collaborative GIT workflows, CI/CD ...
- So the first step for Network IaC is to capture in a repository () all your relevant data being configurations, variables etc ... This allows to to version control your code.

## Content of this repo:
- This repo serves essentially to store code used in NW IaC Workflows. You'll find templates, variables and some golden configurations.
	- templates: Jinja2 files --> ```.j2``` extension.
	- variables: JSON files --> ```.json``` extension.
	- golden configs: Text files --> ```.txt``` extension.
- The content in this repo is used by actions/workflows in other repositories, such as [st2_napalm](https://github.com/mab27/st2_napalm).

