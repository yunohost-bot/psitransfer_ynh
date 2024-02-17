<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# PsiTransfer for YunoHost

[![Integration level](https://dash.yunohost.org/integration/psitransfer.svg)](https://dash.yunohost.org/appci/app/psitransfer) ![Working status](https://ci-apps.yunohost.org/ci/badges/psitransfer.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/psitransfer.maintain.svg)

[![Install PsiTransfer with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=psitransfer)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PsiTransfer quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Simple open source self-hosted file sharing solution. It's an alternative to paid services like Dropbox, WeTransfer.

### Features:

- Mobile friendly responsive interface
- Resumable up- and downloads ([tus.io](https://tus.io))
- Set an expire-time for your upload bucket
- Download all files as zip/tar.gz archive
- Password protected download list ([AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard))
- `/admin` Page lists bucket information (_disabled until you set `adminPass` config value_)


**Shipped version:** 2.1.2~ynh3

## Screenshots

![Screenshot of PsiTransfer](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://psi.cx/tags/PsiTransfer>
* Official admin documentation: <https://github.com/psi-4ward/psitransfer/tree/master/docs>
* Upstream app code repository: <https://github.com/psi-4ward/psitransfer>
* YunoHost Store: <https://apps.yunohost.org/app/psitransfer>
* Report a bug: <https://github.com/YunoHost-Apps/psitransfer_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing --debug
or
sudo yunohost app upgrade psitransfer -u https://github.com/YunoHost-Apps/psitransfer_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>