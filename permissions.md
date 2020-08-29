## Wordpress file permissions fix using ssh

Permissions for wp-config and .htaccess
```
chmod 600 .htaccess

chmod 600 wp-config.php
```


Permission for files
``
find /wordpress/install/path/ -type f -exec chmod 644 {} \;
``

Permission for Directories

``
find /wordpress/install/path/ -type d -exec chmod 755 {} \;
``
