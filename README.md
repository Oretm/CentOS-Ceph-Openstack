# CentOS-Ceph-Openstack

## Scripts and Guides for enviroment setup

```create-journal-on-ssd.sh```
This script used for creating joudnal partitions (4 partitions hardcoded) on drive, that alredy have other partition.

partition that created are logical, firstly created extended partition for all logical.

syntax:

create-journal-on-ssd.sh {device} {size in %}

example:

``` #./create-journal-on-ssd.sh /dev/sde 10```
