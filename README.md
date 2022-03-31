# Openshift LDAP Syncer

Based upon https://docs.okd.io/4.9/authentication/ldap-syncing.html

Syncs LDAP groups into Openshift Groups.

Install:

```
$ git clone https://github.com/getupcloud/openshift-ldapsyncer
$ cd openshift-ldapsyncer
$ cat *.yaml | kubectl apply -f -
```
