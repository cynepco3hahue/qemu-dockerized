# k8s clusters in qemu in docker

* `base` contains the base image with some scripts, qemu and dnsmasq
* `centos7` adds a vagrant centos7 box to the image
* `cli` contains a tool for provisioning, running and managing the containerized clusters
* `k8s-1.9.3` k8s-1.9.3 cluster based on the centos7 image, provisioned with kubeadm
* `os-3.9` os-3.9 cluster based on the centos7 image, provisioned with openshift-ansible

## Versions to use

* `kubevirtci/cli`: `sha256:b0023d1863338ef04fa0b8a8ee5956ae08616200d89ffd2e230668ea3deeaff4`
* `kubevirtci/base`: `sha256:67b84e2acefdcd7197989cbab1f2d1324eb87b5a77bd31d52d3000d13eee750c`
* `kubevirtci/centos:1802_01`: `sha256:31a48682e870c6eb9a60b26e49016f654238a1cb75127f2cca37b7eda29b05e5`
* `kubevirtci/os-3.9:`: `sha256:c214267c1252e51f5ea845ac7868dbc219c63627e9f96ec30cc0a8e9e6e9fc0d`
* `kubevirtci/k8s-1.9.3:`: `sha256:f1506a8aebfb5b5fbf37cd8c9f060bc1f05db683fca15eb11f9fe9e9a58ec9e5`
