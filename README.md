### rpi-homebridge

A docker image that runs the [Homebridge](https://github.com/nfarina/homebridge) iOS HomeKit emulator on raspberry pi


#### usage

map a volume to the homebridge root directory containing your config.json file.

```
$ docker run -d -p 0.0.0.0:51826:51826 -v /opt/homebridge:/root/.homebridge --net=host rcreasey/rpi-homebridge
```
