# Restart Ganglia
A short playbook for restarting all ganglia monitored nodes.

Rename the nodes.example file to nodes and add your monitored nodes in it like 
the given example.

To run the playbook, type 
`ansible-playbook restart-ganglia-monitored-nodes.yml -i nodes`
