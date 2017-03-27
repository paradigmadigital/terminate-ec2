# terminate-instance

Terminate an ec2 instance


# Role Variables

* `instance` : Dictionary containing the information of the instance
  * `id`     : ID of the instance
  * `region` : Region where the instance lives

## Example playbook

```yaml
- hosts: localhost
  connection   : local
  gather_facts : no
  roles:
    - terminate-instance
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
