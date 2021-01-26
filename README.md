# ansible_node_exporter
install a node exporter with ansible on your hosts.

first of all for install node exporter you should edit **hosts** file in provision/inventory/hosts

```
[exporters]
172.43.43.12
172.43.43.11

```

and then run ansible playbook

```
ansible-playbook -i provision/inventory/hosts provision/ansible_node_exporter.yml
```
