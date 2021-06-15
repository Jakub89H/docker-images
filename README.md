# docker-images

network_interface - (Optional) Customize network interfaces to be attached at instance boot time. See Network Interfaces below for more details.
placement_group - (Optional) Placement Group to start the instance in.
private_ip - (Optional) Private IP address to associate with the instance in a VPC.
root_block_device - (Optional) Configuration block to customize details about the root block device of the instance. See Block Devices below for details. When accessing this as an attribute reference, it is a list containing one object.
secondary_private_ips - (Optional) A list of secondary private IPv4 addresses to assign to the instance's primary network interface (eth0) in a VPC. Can only be assigned to the primary network interface (eth0) attached at instance creation, not a pre-existing network interface i.e. referenced in a network_interface block. Refer to the Elastic network interfaces documentation to see the maximum number of private IP addresse
