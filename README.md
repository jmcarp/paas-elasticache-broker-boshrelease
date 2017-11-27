# PaaS ElastiCache Broker Bosh Release

This is a Bosh release for deploying the [ElastiCache broker](https://github.com/alphagov/paas-elasticache-broker) on a Bosh-managed VM. We submodule it into this repository.

# Deploy with BOSH

## Create infrastructure

The broker requires:

* ELB
* security group to access ElastiCache

For example you can use terraform to set this up. The BOSH properties below refer to these components.
