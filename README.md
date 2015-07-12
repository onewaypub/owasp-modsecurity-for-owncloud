# owasp-modsecurity-for-owncloud
this repository conatins adapted and added files for an owncloud installation

whitelist.conf - contains some whitelisted rue ids which should not be applied when you use an owncloud instance
direct-ip-access.conf - contains some rules which block and blacklist direct ip access. This is also part of owasp rule but here we are blocking for a few day

# Other adeption

changed possible mime types and removed all file extension restrictions, because all file extensions are vailed in a cloud

# Note

This verions of rules is currently valid for owncloud 8.x


