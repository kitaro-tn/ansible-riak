# ansible-riak

## Description
It's a riak that was constructed in the ansible

### Riak?
http://docs.basho.com/riak/2.1.3/

## Environment

### Execution environment
- vagrant (>= 1.7)
- serverspec (>= 2.17)
- ansible (>= 2.0.0)

### Build Server
- CentOS 7

## Vagrant setup

```bash
$ vagrant up
```

## Testing

```bash
$ rake spec:_default
```
