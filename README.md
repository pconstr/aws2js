## About

Amazon Web Services node.js module. Originally a fork of [aws-lib](https://github.com/livelycode/aws-lib/). While it resembles some of the aws-lib structure, the internals are moving forward.

## Installation

Either manually clone this repository into your node_modules directory, or the recommended method:

> npm install aws2js

## Project and Design goals

 * HTTPS-only APIs communication
 * Proper error reporting
 * Simple to write clients for a specific AWS service
 * Simple to use AWS API calls
 * Higher level clients for specific work flows (proposed)
 * Proper documentation

## Supported services

 * Amazon EC2 (Amazon Elastic Compute Cloud)
 * Amazon RDS (Amazon Relational Database Service)
 * Amazon SES (Amazon Simple Email Service)
 * Amazon S3 (Amazon Simple Storage Service)

More will come. Remember, this is under active development.

## Usage mode
 * [the EC2 client](https://github.com/SaltwaterC/aws2js/wiki/EC2-Client)
 * [the RDS client](https://github.com/SaltwaterC/aws2js/wiki/RDS-Client)
 * [the SES client](https://github.com/SaltwaterC/aws2js/wiki/SES-Client)
 * [the S3 client](https://github.com/SaltwaterC/aws2js/wiki/S3-Client)

If a specific client doesn't meet your needs, you may implement your own methods via the [config() method](https://github.com/SaltwaterC/aws2js/wiki/The-config%28%29-method).