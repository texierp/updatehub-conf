# Docs


## UHU

1. Push to dashboard
```
$: bitbake updatehub-image-minimal -c uhupush
```

2. Shell

```
$: bitbake updatehub-image-minimal -c uhushell
```

## Updatehub

1. local-server

```
$: updatehub-server /mnt/ --debug
INFO[0000] selected package: /mnt/updatehub-image-minimal-imx7s-warp.uhupkg 
INFO[0000] selected package-uid: cbd5d23691436f770b830b34df0dfd707b9badeb3f7d71908f7ccc50e337ba8b 
DEBU[0000] update metadata loaded: 
...
INFO[0000] UpdateHub Agent is running
INFO[0001] processing HTTP API 'POST /upgrades' request 
INFO[0001] Update available
...
```
