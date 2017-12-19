# Sending Mail with Amazon SES SMTP Server and Java Mail API

## Guide
https://hellokoding.com/form-data-binding-and-validation-example-with-java-spring-boot-and-freemarker/

## What you'll need
- JDK 1.7 or later
- Maven 3 or later
- Amazon SES account
- [SMTP Credentials of your Amazon SES account](http://docs.aws.amazon.com/ses/latest/DeveloperGuide/smtp-credentials.html)
- [Verified From email and To email on SES console](http://docs.aws.amazon.com/ses/latest/DeveloperGuide/verify-addresses-and-domains.html)

## Stack
- Java Mail API

## Run
`mvn clean package exec:java -Dexec.args="{SMTP_USER_NAME} {SMTP_USER_PASSWORD} {FROM_USER_EMAIL} {FROM_USER_FULLNAME} {TO_USER_EMAIL}"`
