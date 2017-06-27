# wekan-snap

wekan server packaged as a snap for Ubuntu core. It consists of:
  - nodejs runtime
  - mongodb
  - wekan server implementation

## How to install

This wekan snap is available in the Ubuntu store for release series 16 (e.g. Ubuntu 16.04). Search for wekan

```
$ sudo snap install wekan
```

At the moment only amd64 target is supported.

Wekan at uappexplorer:

https://uappexplorer.com/snap/ubuntu/wekan

## Help

```
$ wekan.help
```

## How to use

After install, assuming you and the device on which it was installed are on the same network, you should be able to reach the wekan interface by visiting `<device address>`:8080 in your browser, for example http://localhost:8080 .

For more information about wekan refer to https://github.com/wekan/wekan
