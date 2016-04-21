
## openssl-rquery-bash


#### rquery

See my Node HTTP Redis service: https://github.com/evanx/rquery

This service is deployed for public use at: https://redishub.com


### Status

UNSTABLE


### Implementation

See: https://github.com/evanx/openssl-rquery-bash/bin


### Installation

```shell
git clone https://github.com/evanx/openssl-rquery-bash
```

### Usage

```shell
```
where you must specify your keyspace, i.e. substitute `MYKEYSPACE` for your keyspace for your hosts.

You can check a keyspace:
```shell
curl -s https://redishub.com/rquery/ks/MYKEYSPACE/keys | python -mjson.tool
```
```json
```

### Related

See my Node HTTP Redis service: https://github.com/evanx/rquery

Related projects and further plans: https://github.com/evanx/mpush-redis/blob/master/related.md

