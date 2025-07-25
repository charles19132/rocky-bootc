# rocky-bootc

This project aims to provide unofficial Rocky Linux bootc images.

## Building

### Rocky Linux 9

```sh
sudo podman build --cap-add=all --security-opt=label=type:container_runtime_t --device /dev/fuse -t localhost/rocky-bootc:9 -f Containerfile.9 .
```

### Rocky Linux 10

```sh
sudo podman build --cap-add=all --security-opt=label=type:container_runtime_t --device /dev/fuse -t localhost/rocky-bootc:10 -f Containerfile.10 .
```
