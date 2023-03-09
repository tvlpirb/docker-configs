# Docker configs
This repo hosts all the docker configs for my selfhosted servers.

# Caution
Be wary that in many of my compose files, I binded ports to the localhost. By default  
most configs you'll find on the internet bind to 0.0.0.0 but this is actually an issue  
since docker with default settings modifies iptable rules which will bypass UFW or whatever  
firewall you're running. I'd recommend binding to localhost and using a reverse proxy.
