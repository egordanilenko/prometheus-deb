prometheus-deb
===============

DEB packages for products from [prometheus.io](https://prometheus.io/).

[![Build Status](https://travis-ci.org/jtyr/prometheus-deb.svg?branch=prometheus-2.0.0-1)](https://travis-ci.org/jtyr/prometheus-deb)


Packages
--------

Packages are built for the following products:

- [Prometheus](https://github.com/prometheus/prometheus)
- [Alertmanager](https://github.com/prometheus/alertmanager)


Usage
-----

DEB packages produced from this Git repository are served by
[PackageCloud](https://prometheus.io/). You can add the APT repository like
this:

```shell
curl -L https://packagecloud.io/jtyr/prometheus-deb/gpgkey | apt-key add -
echo 'deb https://packagecloud.io/jtyr/prometheus-deb/ubuntu/ xenial main' > /etc/apt/sources.list.d/prometheus.list
apt-get update
apt-get install prometheus
```


Author
------

Jiri Tyr


License
-------

MIT
