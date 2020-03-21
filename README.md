# CloudWatch Install

The bash script handles server logging for sending log entries to [AWS CloudWatch Logs](http://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html) service. Before using this script, it's recommended to get acquainted with the [pricing](https://aws.amazon.com/en/cloudwatch/pricing/) for AWS CloudWatch services.

## Features

* Up to 10000 batch logs sending in order to avoid _Rate exceeded_ errors
* Log Groups creating with tags
* AWS CloudWatch Logs staff lazy loading
* Suitable for applications on the AWS cloud
* Compatible with PHP >= 5.6

## Prerequisites and Installation

* Make it executable:

```chmod +x cloudwatch-install.sh```

* Run the script:

```sudo ./cloudwatch-install.sh```

## License

The script is published under [BSD 3-Clause License](license.txt).

## Copyright

(c) 2018 [Cloudeya Limited](https://www.cloudeya.co.uk).