# AWS Cloud Development Kit (CDK) Primer

## Table of Contents

## What is AWS CDK?
* Is a SDK for defining cloud infrastructure as code.
* How it works under the hood:
    * Acts as a compiler to compile your IaC into an AWS CloudFormation template.
    * You write your code in a supported programming language (TypeScript, JavaScript, Python, Java, C#). Then the AWS CDK compiler uses AWS JSii (a JS interoperability framework) to compile your code into a CloudFormation template.
* Developer interacts with AWS CDK and its three main components (App, Stack, and Construct) to create an AWS CloudFormation template

## Core framework of AWS CDK
* Constructs
    * A construct is a cloud component that represents one or more AWS resources.
    * Can represent a single resource or a collection of resources.
    * Can be reused as a component in other constructs.
    * Can be used to create higher-level abstractions.
* Stacks
    * A stack is a collection of constructs that represent a single AWS CloudFormation stack.
    * A stack can contain multiple constructs.
    * A stack can be deployed to an AWS account.
* Apps
    * An app is a collection of stacks.
    * An app can contain multiple stacks.
    * An app can be deployed to an AWS account.


## Advantages of using AWS CDK
* Faster deployment by using expressiveness of programming languages for defining infrastructure.
* Use programming language features such as loops, conditions, functions, classes, and inheritance to define infrastructure.
* Use IDE features such as code completion, syntax checking, and refactoring to define infrastructure.
* Use programming language tools such as unit testing, integration testing, and debugging to define infrastructure.
* Share and reuse your infrastructure as libraries. 
