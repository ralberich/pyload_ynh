# pyLoad pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pyload.svg)](https://dash.yunohost.org/appci/app/pyload) ![](https://ci-apps.yunohost.org/ci/badges/pyload.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pyload.maintain.svg)  
[![Installer pyLoad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pyload)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer pyLoad rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

The free and open-source Download Manager written in pure Python


**Version incluse :** 0.4.20~ynh2



## Captures d'écran

![](./doc/screenshots/sample.png)

## Avertissements / informations importantes

-   Default username: `pyload`.
-   Default password: `pyload`.

**It's highly recommended to change the default access credentials on first start**.

## Documentations et ressources

* Site officiel de l'app : https://pyload.net
* Documentation officielle de l'admin : https://github.com/pyload/pyload/wiki
* Dépôt de code officiel de l'app : https://github.com/pyload/pyload
* Documentation YunoHost pour cette app : https://yunohost.org/app_pyload
* Signaler un bug : https://github.com/YunoHost-Apps/pyload_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pyload_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pyload_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pyload -u https://github.com/YunoHost-Apps/pyload_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps