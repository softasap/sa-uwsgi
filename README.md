sa-uwsgi
========

[![Build Status](https://travis-ci.org/softasap/sa-uwsgi.svg?branch=master)](https://travis-ci.org/softasap/sa-uwsgi)

uwsgi in emperor mode.

Upstart supported: upstart, systemd, supervisord


Example of usage (all parameters are optional)

Simple

```YAML
  roles:
    - {
        role: "sa-uwsgi",
      }
```

Advanced:

```YAML
  roles:
    - {
        role: "sa-uwsgi",
        option_install_python: true,
        option_install_python3: true,
        uwsgi_pip:  pip3  # install uwsgi using provided pip path

      }
```


Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
