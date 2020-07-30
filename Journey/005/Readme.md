![Image of the ocean](https://images.unsplash.com/photo-1595905710082-d7a71b6b3d36?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1351&q=80)

# Setting up an EC2 Instance

## Introduction

Setting up EC2 instances can be used to host a webserver or anything that needs compute power. Something I'd use it for is hosting a discord bot if I needed to.

## Use Case

Setting up an Apache server would require compute power which makes EC2 a good candidate for the task.

## Cloud Research

Setting up an EC2 instance is fairly straight forward, don't need to modify any settings really besides maybe editing security group rules to allow SSH traffic but everything else should be default. I had some trouble connecting to my instance because I had messed around with some network ACL rules which were stopping me from connecting but eventually I solved it.
