# bgp-peer 
1. Gather device facts
2. Use facts to created a named configuration file (named by discovered hostname) from variables in a yaml file fed into a jinja2 template
3. Load a pre-existing bgp policy file based on device hostname and the bgp configuration file created from the template to a device
4. Commit the configuration


