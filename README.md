docker-kvm-shelf-rhel6
======================

[buildshelf-rhel6-setup](https://github.com/hansode/buildshelf-rhel6-setup) based buildshelf for Docker host on KVM

Requirements
------------

+ RHEL/CentOS/Scientific
+ [KVM](http://www.linux-kvm.org/page/Main_Page)
+ [Docker](https://github.com/dotcloud/docker)

Getting Started
---------------

Setup submodules.

```
$ make setup
```

Build VM image for Docker box.

```
$ cd roles/kvm.docker-host
$ make
```

Run VM.

```
$ sudo ./run.sh
```

Connect to serial-port.

```
$ telnet localhost 5099
```

Links
-----

+ [buidbook-rhel6](https://github.com/hansode/buildbook-rhel6)
+ [vmbuider](https://github.com/hansode/vmbuilder)

License
-------

[Beerware](http://en.wikipedia.org/wiki/Beerware) license.

If we meet some day, and you think this stuff is worth it, you can buy me a beer in return.
