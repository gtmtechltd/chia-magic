chia-magic
==========

A collection of useful utilities to help multi-node plot chia setups.

To run on a farm node (with or without hpool mining):

```
cycle-disks:                 A utility to keep hard drives spinning for faster access when needed"
cycle-hpool:                 A utility to quickly bounce the hpool-miner process to pick up new plots. Add to cron
start-chia:                  Start chia GUI
usb-transfer:                A utility to move files off a USB disk into the emptiest farm directory
watch-all:                   A utility to provide useful commandline info about status of plots and chia mainnet node
watch-uploads:               A utility to provide useful updates as to uploads to the farmer node
```

To run on any plotting node

```
start-chiafactory-downloads: Start downloading plots from chiafactory (Requires chiafactory-simple-download) 
uploadplots:                 As soon as plots appear in local dir, upload them to farmer node
viplotman-mac:               Got sick of remembering where the plotman.yaml file was. Use this instead
viplotman-linux:             Got sick of remembering where the plotman.yaml file was. Use this instead
watch-plotman:               A utility to provide useful updates as to plotman plots
```

For best results

* Connect your plotting nodes to farming nodes by cat7 network cable and gigabit n-port hub, not wifi.

See also:

* [chiafactory-simple-download](https://github.com/gtmtechltd/chiafactory-simple-download)

