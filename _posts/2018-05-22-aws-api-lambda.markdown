---
layout: post
category: "aws"
title:  "Use Lambda in AWS API Gateway"
tags: [lambda, api gateway]
---

## Lambda-Proxy vs Lambda Integration in AWS API Gateway
 5/22/2018 4:37:22 PM 
>  refer to [https://medium.com/@lakshmanLD/lambda-proxy-vs-lambda-integration-in-aws-api-gateway-3a9397af0e6d](https://medium.com/@lakshmanLD/lambda-proxy-vs-lambda-integration-in-aws-api-gateway-3a9397af0e6d "Lambda-Proxy vs Lambda Integration in AWS API Gateway")

### What is API Gateway?
AWS API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. Lambda is function as a service(FAAS) product of AWS. The combination of these two services is amazing and it is slowly replacing the traditional backend. The combination is serverless, cost-efficient and infinitely scalable.

### API Gateway integrations
API Gateway has many integrations, but this post is all about the possible integrations between API Gateway and Lambda. The two possible integrations are Lambda-Proxy and Lambda. I had a tough time understanding them, so I am going to document their features, pros, cons and instructions to setup in a comprehensible way. If you know about them and just want to set it up, jump to the instructions part.

### Lambda-Proxy vs Lambda Integration
![](https://cdn-images-1.medium.com/max/1000/1*n7nWIzzmj-EoP6ptcQDQAA.png)
**General Description**  
| Name | Academy | score |   
| - | :-: | -: |   
| Harry Potter | Gryffindor| 90 |   
| Hermione Granger | Gryffindor | 100 |   
| Draco Malfoy | Slytherin | 90 |   
