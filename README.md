# fly-uptime-kuma

To host uptime kuma on Fly.io clone this repo, enter the folder and run:

```
fly launch \
  --copy-config \
  --auto-confirm \
  --ha=false \
  --now
```

You will be asked an app name and organization. A 1GB volume will be created on deploy.

