# Wemeet

## Notice

This package embedded [wemeet-wayland-screenshare](https://github.com/xuwd1/wemeet-wayland-screenshare) to enable screenshare on Wayland

The hook is enabled by default, to disable it:

```sh
flatpak override --user --unset-env=LD_PRELOAD com.tencent.wemeet
```

And to re-enable:

```sh
flatpak override --user --env=LD_PRELOAD=/app/lib/wemeet/libhook.so com.tencent.wemeet
```

