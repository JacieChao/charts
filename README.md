# charts

## Live Branch

The following directory structure is expected:
```text
assets/
  <package>/
    <chart>-<packageVersion>.tgz
  ...
charts/
  <package>
    <chart>
      <packageVersion>
        # Unarchived Helm chart
```
   
## mirror 镜像

请先将下列镜像 mirror 到内部私有镜像仓库：

- quay.io/tigera/operator:v1.36.5
- calico/node:v3.29.2
- calico/pod2daemon-flexvol:v3.29.2
- calico/cni:v3.29.2
- calico/typha:v3.29.2
- calico/kube-controllers:v3.29.2