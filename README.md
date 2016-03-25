# httpConcierge
http proxy to alter traffic for security and logging purposes

This script forwards a number of configured local ports to another local and a remote socket servers.

Configuration:
Add to the config file port-forward.config lines with contents as follows:

Error messages are stored in file 'error.log'.

The script splits the parameters of the config file:
Split each config-line with spaces
0: local port to listen to
1: local port to forward to
2: remote ip adress of destination server
3: remote port of destination server
and return settings
