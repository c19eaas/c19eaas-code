---
title: "Contact"
layout: contact
description:
draft: false
---

We are currently working on our next generation email contact system, which will use an AWS Lambda hosted microservice to generate an SQS message that is picked up by 3 microservices: one to send us an email via SNS, one to log the same content to CloudWatch, and one to store the email in S3.

In the meantime, we ask that you simply <a href="mailto:c19eaas@protonmail.com">send us an email</a> directly via your email client.
