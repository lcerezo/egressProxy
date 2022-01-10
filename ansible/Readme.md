suitabelf for use in instance profile.

```
/usr/bin/ansible-playbook -e @PATHTO_JSON/aws.${environment}.squid.dict.json --connection=local -i localhost, PATH_TO/ansible/ec2-local.site.yml
```