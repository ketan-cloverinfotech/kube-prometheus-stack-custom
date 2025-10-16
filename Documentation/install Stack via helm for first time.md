# install Stack via helm for first time
```
helm upgrade --install clover-monitoring \ oci://ghcr.io/ketan-cloverinfotech/clover-monitoring/clover-monitoring \ --version 0.1.1 \ -n monitoring --create-namespace
```
# Pull helm chart
```
helm pull oci://ghcr.io/ketan-cloverinfotech/clover-monitoring/clover-monitoring \
  --version 0.1.1
```
