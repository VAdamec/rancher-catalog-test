# Basic info

- Cannot create certificate, only update already existing certificate via Rancher API

## Prerequisites before launch
- Vault
 - Vault with PKI enabled and policy setup
 - Valid token (client can do token revalidation)
- Rancher
 - Rancher with existing certitificate
 - Rancher environment ID
 - ID and name of the certificate
 - Rancher access and secure key
