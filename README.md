# Full-Text-RSS for Yunohost

[![Integration level](https://dash.yunohost.org/integration/full-text-rss.svg)](https://dash.yunohost.org/appci/app/full-text-rss) ![](https://ci-apps.yunohost.org/ci/badges/full-text-rss.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/full-text-rss.maintain.svg)

[![Install Custom Webapp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=full-text-rss)

> *This package allow you to install Full-Text-RSS quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Full-Text RSS can transform partial web feeds — often summary-only feeds which expect you to visit cluttered, ad-ridden site to read the full story — to deliver the full content stripped of clutter and ads.
Read articles in full, in peace, in your favourite news reading application.

**Shipped version:** 3.8
**License:** [AFFERO GENERAL PUBLIC LICENSE v3](https://bitbucket.org/fivefilters/full-text-rss/src/master/license.txt)

## Screenshots
![screenshot full-text-rss](https://desaille.fr/wp-content/uploads/2015/05/rss.jpg "full-text-rss screenshot")

## Demo
[Demo on official site](https://fivefilters.org/content-only/)

## Configuration
Edit `custom_config.php` in `/var/www/YOUR_PATH/custom_config.php`

Access web admin area in http://yourdomain/your_path/admin/

## Documentation

## YunoHost specific features

#### Multi-users support


#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/full-text-rss%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/full-text-rss/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/full-text-rss%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/full-text-rss/)

## Limitations

## Additional information

## Links
* Full-Text-RSS website: https://fivefilters.org/content-only/

## To Do

- [ ] Remove extraction_rules download
- [ ] If site is private, only open RSS feed
- [ ] Problème de droit sur config_standard
---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/full-text-rss_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/full-text-rss_ynh/tree/testing --debug
or
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/full-text-rss_ynh/tree/testing --debug
