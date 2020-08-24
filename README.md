# ansible_patching
Patching of systems via ansible

This is meant to be run from AWX or Tower instance

Hosts are set to "all" so that this can be run properly after being added as a project in AWX


Reporting functionality will be added in the future. Currently Discord is supported.
If you need to use discord add an extra variable in tower called
discord_webhook_url: 
with your webhook in it.