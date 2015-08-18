# Synopsis
Sets the DNS servers for a remote system.

# Description
This scripts takes a single server or a list of servers and updates the DNS configuration remotely. It will overwrite the existing configuration on all enabled adapters.

You can specify either a single server name or multiple comma seperated names in the `-ComputerName` parameter.

# Notes
Be sure to update the values on line 20 to match your environment.