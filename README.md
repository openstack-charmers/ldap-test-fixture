# Description

This charm performs a basic LDAP install (including phpldapadmin), and loads
the LDAP server with a pre-defined set of user data (see files/backup.ldif).

The top-level domain is `dc=test,dc=com`.

The users are:

    johndoe
    janedoe

The password for each is 'crapper'.

The password for the admin administrator (cn=admin,dc=test,dc=com) on the
server is also 'crapper'.
