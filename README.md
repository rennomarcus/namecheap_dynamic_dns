namecheap_dynamic_dns
=====================

A script which will update an A record, setting its value to the external ip returned by ipecho.net, for any namecheap domain with dynamic DNS enabled

configuration
=============

update_namecheap_dns_record.sh requires the following configuration items to be set.  They can either be set in ~/.namecheap_dynamic_dns, or can be set in the environment when executed:

```
NAMECHEAP_PASSWORD=123123123123123123
NAMECHEAP_HOSTNAME=[your hostname]
NAMECHEAP_DOMAIN=[your domain name]
```
