# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-webui_1.4.0_amd64.rock docker-daemon:sdcore-webui:1.4.0
docker run sdcore-webui:1.4.0
```
