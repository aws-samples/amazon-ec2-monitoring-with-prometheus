## amazon-ec2-monitoring-with-prometheus

This repository contain solution for automating Amazon EC2 monitoring using Prometheus EC2 service discovery and AWS Distro for OpenTelemetry(ADOT) collector.

## Solution Architecture
![Solution Architecture](/resources/ec2_sd_diagram_archiecture-Simple%20Scrape.jpg)

You can read the [blog post](https://aws.amazon.com/blogs/mt/automating-amazon-ec2-instance-monitoring-with-prometheus-ec2-service-discovery-and-aws-distro-for-opentelemetry/) for deployment steps and more information.

## Troubleshooting
1. If you see the following error while deploying the CFN stack, please make sure you have IAM Identity Center enabled in your AWS Account/Region.

`Error: Resource handler returned message: "SSO is not enabled in any region.`
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

