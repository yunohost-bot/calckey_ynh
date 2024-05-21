<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Calckey for YunoHost

[![Integration level](https://dash.yunohost.org/integration/calckey.svg)](https://dash.yunohost.org/appci/app/calckey) ![Working status](https://ci-apps.yunohost.org/ci/badges/calckey.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/calckey.maintain.svg)

[![Install Calckey with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=calckey)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Calckey quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

A greatly enhanced fork of Misskey with better UI/UX, security, features, and more! https://i.calckey.cloud/


    Calckey is based off of Misskey, a powerful microblogging server on ActivityPub with features such as emoji reactions, a customizable web UI, rich chatting, and much more!
    Calckey adds many quality of life changes and bug fixes for users and instance admins alike.
   


**Shipped version:** 14.0.0rc3~ynh1

**Demo:** <https://i.calckey.cloud/>

## Screenshots

![Screenshot of Calckey](./doc/screenshots/screenshot-calckey.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: Calckey has been replaced by Firefish, install that new app instead. A migration procedure is being developed for existing instances.

## Documentation and resources

- Official app website: <https://i.calckey.cloud/>
- Upstream app code repository: <https://codeberg.org/calckey/calckey>
- YunoHost Store: <https://apps.yunohost.org/app/calckey>
- Report a bug: <https://github.com/YunoHost-Apps/calckey_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/calckey_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
or
sudo yunohost app upgrade calckey -u https://github.com/YunoHost-Apps/calckey_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
