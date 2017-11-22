## Introduction to AWS Elastic Beanstalk(EB)
### Basic Set Up
Complex shapes can be created using shape generator. [reference](https://colintoh.com/blog/aws-elastic-beanstalk-survival-guide-introduction)  
The packages required are:
* Python 3.4
* pip
* virtualenv
* awsebcli

First create a virtual environment called eb-virt
```
virtualenv eb-virt
```
Activate the environment by
```
eb-virt\Scripts\activate
```
install the required packages by using
```
pip install django==1.9.12
```
If get a *PermissionError: [WinError 5] Access is denied*, try
```
python -m pip install django
easy_install django
```
List all libraries installed, run
```
pip freeze
pip list
```
### Using EB CLI tool
**eb** provides us with high-level commands to manage and configure our Elastic Beanstalk applications within the terminal.  
Below are some important **eb** commands:
* eb init - Creating Application
* eb create - Creating environment
* eb console - Opening Elastic Beanstalk Dashboard
* eb list - Show current environment
* eb use - Switch environment
* eb logs - Logs Checking
* eb deploy - Deployment  
The full list of **eb** commands can be found [here](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb3-cmd-commands.html)
