This is an example configuration for preparing a web server AWS EC2 instance with an elastic nic.

To build:
Ensure you have setup AWS profile on local device then run

> terraform init

To apply configuration:

> terraform apply [optional: --auto-approve]

[Optional parameter ]

Full list of resources created:
aws_eip.elip
aws_instance.web-server-instance-1
aws_internet_gateway.gw
aws_network_interface.web_server_nic
aws_route_table.prod_route_table
aws_route_table_association.a
aws_security_group.allow_web
aws_subnet.subnet_1
aws_subnet.subnet_2
aws_vpc.prod_vpc
