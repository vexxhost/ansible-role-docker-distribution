# ansible-role-docker-distribution

## Examples

### Pass-through cache
```yaml
- hosts: registry
  roles:
    - docker-distribution
  vars:
    docker_distribution_proxy:
      remoteurl: https://registry-1.docker.io
```