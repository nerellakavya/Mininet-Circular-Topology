# Mininet-Circular-Topology

Sample network for circular topology network which takes number of switches and hosts as input. A characteristic of this network is that the odd numbered hosts ping only odd numbered where as even numbered hosts ping only even numbered hosts.

## Technologies

Pox Controller and Mininet

## To Run

```
sudo python ~/pox/pox.py forwarding.l2_multi openflow.discovery --eat-early-packets openflow.spanning_tree --no-flood --hold-down
```
Once the controller is up, run the following command
```
sudo python mininet.py
```
