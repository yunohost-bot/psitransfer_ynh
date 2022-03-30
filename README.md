<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# PSITransfer for YunoHost

[![Integration level](https://dash.yunohost.org/integration/psitransfer.svg)](https://dash.yunohost.org/appci/app/psitransfer) ![](https://ci-apps.yunohost.org/ci/badges/psitransfer.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/psitransfer.maintain.svg)  
[![Install PSITransfer with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=psitransfer)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PSITransfer quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Simple open source self-hosted file sharing solution.
It's an alternative to paid services like Dropbox, WeTransfer.

* No accounts, no logins
* Mobile friendly responsive interface
* Supports many and very big files (Streams ftw)
* Resumable up- and downloads ([tus.io](https://tus.io))
* Set an expire-time for your upload bucket
* One-time downloads
* Download all files as zip/tar.gz archive
* Modal-style file preview
* Requires Node >=7.4 or use `--harmony-async-await` flag
* Password protected download list ([AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard))
* `/admin` Page lists bucket information, [Screenshot](https://raw.githubusercontent.com/psi-4ward/psitransfer/master/docs/PsiTransfer-Admin.png) (_disabled until you set `adminPass` config value_)
* Lightweight [Vue](https://vuejs.org) based frontend apps. Gzipped (on by default) less than 100k
* Explicit named bucket IDs with query param `sid=<myBucketID>`


**Shipped version:** 1.12.0~ynh1



## Screenshots

![](./doc/screenshots/psitransfer.gif)

## Documentation and resources

* Official app website: https://psi.cx/tags/PsiTransfer
* Official admin documentation: https://github.com/psi-4ward/psitransfer/tree/master/docs
* Upstream app code repository: https://github.com/psi-4ward/psitransfer
* YunoHost documentation for this app: https://yunohost.org/app_psitransfer
* Report a bug: https://github.com/YunoHost-Apps/psitransfer_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing --debug
or
sudo yunohost app upgrade psitransfer -u https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps