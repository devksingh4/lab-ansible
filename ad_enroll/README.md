# Description
This Ansible workbook will enroll Debian/Ubuntu nodes into Active Directory.

# Instructions 
Create `roles/domain_join/vars/secrets.yml` with the following contents:

```yaml
---
kerberos_user: svc-adenroll
kerberos_user_password: {pull from bitwarden}
```
