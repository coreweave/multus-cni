# Multus-CNI

This is a minor fork of upstream [k8snetworkplumbingwg/multus-cni](https://github.com/k8snetworkplumbingwg/multus-cni), currently based on v3.7.1. 

This fork sorts device IDs in the pod resource map, to workaround a kubevirt sriov bug. 
