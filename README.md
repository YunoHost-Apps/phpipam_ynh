# phpIPAM app for YunoHost
phpIPAM Server

**Shipped version:** 1.4

- [Yunohost project](https://yunohost.org)
- [phpIPAM website](https://phpipam.net/)

![](https://phpipam.net/css/images/phpipam_logo_small@2x.png)


[![Install phpIPAM with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=phpipam)

### Installing guide

 App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh
         
        1. Login in phpIPAM
        2. put your sql user and password 
        (you can find them via "nano /var/www/phpipam/config.php" in cli mode)
        3. Admin user for db is same user for sql same for password

 
### Upgrade this package:

        $ sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh

