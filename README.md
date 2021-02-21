# Enterprise Search with Amazon Kendra

This lab is provided as part of **[AWS Innovate AI/ML Edition](https://aws.amazon.com/events/aws-innovate/machine-learning/)**, click [here](https://github.com/phonghuule/aws-innovate-ai-ml) to explore the full list of hands-on labs.

ℹ️ You will run this lab in your own AWS account. Please follow directions at the end of the lab to remove resources to avoid future costs.

## Overview
In this workshop we will be using Amazon Kendra to setup our own Enterprise Search instance, index HTML/PDF content in Amazon S3, and use a variety of query types to return accurate search results for end users.

**Note: Amazon Kendra pricing and free tier information is available at https://aws.amazon.com/kendra/pricing/. You should delete your index after you are done with this workshop to avoid Kendra related charges.**

This workshop is split into 3 parts:

[Part 1 - Creating a Kendra Index](https://github.com/phonghuule/enterprise-search-with-amazon-kendra-workshop/blob/master/Part%201%20-%20Creating%20a%20Kendra%20Index.md) 

In Part 1, we will create the Kendra index. Here we will also be populating our search repository with some sample data from the Amazon Sagemaker documentation and some Machine Learning whitepapers. At the end of this section we will be able to search over our repository and return results to users.

[Part 2 - Adding Frequently Asked Questions (FAQ)](https://github.com/phonghuule/enterprise-search-with-amazon-kendra-workshop/blob/master/Part%202%20-%20Adding%20a%20FAQ.md)

In Part 2, we will enhance our existing index with Frequently Asked Questions (FAQ). This will allow users to quickly get directly to answers for common questions. Our dataset in this case is the Amazon Sagemaker FAQs.

[Part 3 - Adding Metadata](https://github.com/phonghuule/enterprise-search-with-amazon-kendra-workshop/blob/master/Part%203%20-%20Adding%20Metadata.md)

In the final section of this workshop, we will go even further in enriching the search experience for end users by building metadata objects to go with the document repository. This metadata will allow us to override certain elements such as the title of a document, or add other metadata that we can use for faceted search.

[Part 4 - Clean Up](https://github.com/phonghuule/enterprise-search-with-amazon-kendra-workshop/blob/master/Part%204%20-%20Clean%20Up.md)

Lastly we will clean up the resources we created.

## Survey
Please help us to provide your feedback [here](https://amazonmr.au1.qualtrics.com/jfe/form/SV_b7mXqfAaiIZUnn8?Session=Lab3).
Participants who complete the surveys from AWS Innovate Online Conference - AI & Machine Learning Edition will receive a gift code for USD25 in AWS credits. AWS credits will be sent via email by 31 March, 2021.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.
