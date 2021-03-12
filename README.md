# kata

```
chown -R root:docker /opt/kata

# Resolve vhost_vsock: Device or resource busy
vim /etc/modprobe.d/blacklist-vmware.conf
    blacklist vmw_vsock_virtio_transport_common
    blacklist vmw_vsock_vmci_transport
```

https://blog.csdn.net/kunyus/article/details/106986621


