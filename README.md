# bgp-peer is specific to one device (R1) but can be amended to apply to multiple devices by replacing R1 with {{ inventory_hostname }}
1. Gather device facts
2. Use facts to created a named configuration file from variables in a yaml file fed into a jinja2 template
3. Load a pre-existing bgp policy file and the bgp configuration file created from the template to a device
4. Commit the configuration


