# kubernetes-3-node-notes
My 2019 Kubernetes Build Notes

Ubuntu 18.04
Vmware

Fix customization

https://kb.vmware.com/s/article/56409


<b>Prep Ubuntu for vmware template:</b>

https://raw.githubusercontent.com/mkeguy106/Ubuntu-18.04-SysPrep/master/Ubuntu%2018.04%20Sysprep.sh
Using DHCP in my network.  Big key to sysprep is clearing out /etc/machine-id file contents, so each node has a unix duid. Otherwise, after vmware cloning, each node is assigned the same ip(not good).

Following Kubernetes Guide:

https://computingforgeeks.com/how-to-setup-3-node-kubernetes-cluster-on-ubuntu-18-04-with-weave-net-cni/

