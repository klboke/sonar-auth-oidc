# OpenID Connect (OIDC) Plugin for SonarQube
- fork : https://github.com/vaulttec/sonar-auth-oidc 

- fix : https://github.com/vaulttec/sonar-auth-oidc/issues/51

warning : Using this plugin, we will map OIDC authorized users directly with their original login names. This means that if there is an admin account in the system, and if there is a username in OIDC that is also admin, they will be considered to be the same person