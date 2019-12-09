# Creating and Deploying \.NET Applications on AWS Elastic Beanstalk<a name="create_deploy_NET"></a>

Elastic Beanstalk for \.NET makes it easier to deploy, manage, and scale your ASP\.NET web applications that use Amazon Web Services\. Elastic Beanstalk for \.NET is available to anyone who is developing or hosting a web application that uses IIS\.

**Get started now**: To get started with a tutorial, you can go directly to [Tutorial: How to Deploy a \.NET Sample Application Using AWS Elastic Beanstalk](create_deploy_NET.quickstart.md)\. In this tutorial, you will deploy a sample ASP\.NET Web Application to an AWS Elastic Beanstalk application container\.

The rest of this section presents instructions for creating, testing, deploying, and redeploying your ASP\.NET web application to Elastic Beanstalk\. Some examples demonstrate using the AWS Toolkit for Visual Studio, and [The AWS Toolkit for Visual Studio](dotnet-toolkit.md) subsection explains how to manage and configure your applications and environments using the toolkit\. For more information about prerequisites, installation instructions, and running code samples, go to the [AWS Toolkit for Microsoft Visual Studio](https://aws.amazon.com/visualstudio/)\. This site also provides useful information about tools, how\-to topics, and additional resources for ASP\.NET developers\.

**Note**  
This platform doesn't support the following Elastic Beanstalk features:  
Worker environments\. For details, see [AWS Elastic Beanstalk Worker Environments](using-features-managing-env-tiers.md)\.
Bundle logs\. For details, see [View Instance Logs](using-features.logging.md)\.
In addition, platform versions earlier than v2\.0\.0 don't support enhanced health reporting, managed platform updates, immutable updates, immutable deployments, and rolling deployments with an additional batch\.

The topics in this chapter assume some knowledge of Elastic Beanstalk environments\. If you haven't used Elastic Beanstalk before, try the [getting started tutorial](GettingStarted.md) to learn the basics\.

**Topics**
+ [Getting Started with \.NET on Elastic Beanstalk](dotnet-getstarted.md)
+ [Setting Up your \.NET Development Environment](dotnet-devenv.md)
+ [Using the AWS Elastic Beanstalk \.NET Platform](create_deploy_NET.container.console.md)
+ [Tutorial: How to Deploy a \.NET Sample Application Using AWS Elastic Beanstalk](create_deploy_NET.quickstart.md)
+ [Deploying an ASP\.NET Core Application with AWS Elastic Beanstalk](dotnet-core-tutorial.md)
+ [Adding an Amazon RDS DB Instance to Your \.NET Application Environment](create_deploy_NET.rds.md)
+ [The AWS Toolkit for Visual Studio](dotnet-toolkit.md)
+ [Migrating Your On\-Premises \.NET Application to Elastic Beanstalk](dotnet-onpremmigration.md)
+ [Resources](create_deploy_NET.resources.md)