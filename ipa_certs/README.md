# ipa_certs
# Generate Idm HTTP Certs for system web service and manage with certmonger

- creates a service principal
- creates private, public keys, csr and generates an IPA signed cert
- ensures certmonger is monitoring the cert for renewal

### Tested with:
ipa --version
VERSION: 4.5.0, API_VERSION: 2.228

