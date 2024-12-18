# kvm-exporter

Prometheus exporter for KVM

* host
    * [prometheus/node_exporter: Exporter for machine metrics](https://github.com/prometheus/node_exporter?tab=readme-ov-file)
* virtual machine
    * [bykvaadm/libvirt_exporter_improved: Prometheus metrics exporter for libvirt.](https://github.com/bykvaadm/libvirt_exporter_improved)

## Usage
* [ERROR - Deploy - Error response from daemon: linux mounts: path / is mounted on / but it is not a shared or slave mount. · Issue #2002 · prometheus/node_exporter](https://github.com/prometheus/node_exporter/issues/2002)
```bash
mount --make-rshared /
```

```
git clone https://github.com/arakkkkk/kvm-exporter.git
cd kvm-exporter
docker compose up -d
```
