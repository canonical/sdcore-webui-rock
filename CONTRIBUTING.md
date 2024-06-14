# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-webui_1.4.1_amd64.rock docker-daemon:sdcore-webui:1.4.1
docker run sdcore-webui:1.4.1
```
