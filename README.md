# prometheus-operator-multi-arch
Multi-Arch Images for https://github.com/coreos/prometheus-operator

## Versioning

Images following the same versioning as the upstream repo.

## Images

### Operator

```
docker pull docker.io/rmb938/prometheus-operator-multi-arch:$VERSION
```

### Prometheus Config Reloader

```
docker pull docker.io/rmb938/prometheus-config-reloader-multi-arch:$VERSION
```

## Supported Architectures 

* amd64
* arm (arv7/armfh) - Tested on Rasbian Buster
* arm64 - Tested on Ubuntu 20.04 Raspberry Pi 

To request other architectures please make an issue or open a pull requiest. 
