# Week 0 — Billing and Architecture

# Required Homework 

## I was able to install and use AWS CLI on giptod.
I followed these steps from the [AWS command line docs and userguide page](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html#cliv2-linux-install) to install the AWS CLI on gitpod.

```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```

Here's a image of what it looked like after intallation.
![required homework prove](https://user-images.githubusercontent.com/123770803/235026963-910cccc5-0dba-4809-af75-41c4072df5ed.png)

## I was able to set Enviromental Variables for my cloud credentials.
Environment variables provide another way to specify configuration credentials

I was able to set Enviromental Variables for my credentials by following this examples on the [AWS Enviroment Variables doc page](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-envvars.html)

```
export AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
export AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
export AWS_DEFAULT_REGION=us-west-2
```
Here's a image of the my output after setting Enviromental Variables and calling the Caller-identity
![prove of AWS CLI](https://user-images.githubusercontent.com/123770803/235029982-349b52a6-8573-4884-b33b-992f89a13a92.png)
