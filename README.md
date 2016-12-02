Zimbra Talk localization and translation
==========

This public repository contains the localization files for Zimbra Talk. The intention is to easily enable users and partners to contribute to the localization effort.


## How to create a new translation file

1. create a new property file in admin or client directory based on the default property file. The filename has to contain the locale information asdescribed in https://wiki.zimbra.com/wiki/Zimlet_Developers_Guide:Internationalization#Properties_File_Naming_Convention
The easiest way is to create a copy of the default file biz_zcs_vnc_talk_zimlet.properties or biz_vnc_admin_talk_zimlet.properties
2. Translate all the properties to match your language. Make sure to escape all non-ASCII characters in javascript escaping. On linux systems uni2ascii is the preferred tool - otherwise use this online converter: https://r12a.github.io/apps/conversion/
3. Send a pull request.
4. New translations will be integrated into the product.

## Development in progress

Since Zimbra Talk is constantly in development to improve and enhace the system, new translation requirements will come up from time to time. We will notify all contributors when new translations are required.
