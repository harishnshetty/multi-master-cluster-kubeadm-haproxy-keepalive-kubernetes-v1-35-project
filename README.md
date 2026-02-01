# multi-master-cluster-kubeadm-haproxy-keepalive-kubernetes-v1-35-project




## install the HAProxy and KeepAlived

- ha01
- ha02

```bash
sudo apt update
sudo apt install keepalived haproxy -y
```
vim/etc/haproxy/haproxy.cfg