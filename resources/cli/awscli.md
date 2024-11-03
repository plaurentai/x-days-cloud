This is how I install the AWS CLI on my MacBook Air. I am using homebrew for the install. This tutorial assumes HomeBrew is already installed:

1. brew update
2. brew install awscli
3. aws --version

## Using the AWS CLI

This section assumes an identity is already created as well as the AWS access key needed to interact with AWS from the command line. From the terminal type the followings:

- $ export AWS_ACCESS_KEY_ID=XXXXXXX
- $ export AWS_SECRET_ACCESS_KEY=xxxxxxxxxx
- $ export AWS_DEFAULT_REGION=us-east-1

## Let's see if they are any instances running

- $ aws ec2 describe-instances

As you can see there are no instances of ec2 running:

```
jude@pyai x-days-cloud % aws ec2 describe-instances
{
    "Reservations": []
}

```





