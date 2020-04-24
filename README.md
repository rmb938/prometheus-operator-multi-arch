# prometheus-operator-multi-arch
Multi-Arch Images for https://github.com/coreos/prometheus-operator

## Versioning

Images following the same versioning as the upstream repo.

## Images

### Operator

```
docker pull docker.io/rmb938/prometheus-operator-multi-arch:$VERSION-$ARCH
```

### Prometheus Config Reloader

```
docker pull docker.io/rmb938/prometheus-config-reloader-multi-arch:$VERSION-$ARCH
```

## Supported Architectures 

* amd64
* arm (arv7/armfh) - Raspberry Pi Compatible

To request other architectures please make an issue or open a pull requiest. 
