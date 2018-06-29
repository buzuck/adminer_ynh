# Adminer for Yunohost
Shipped Version: **4.6.3**
Adminer (formerly phpMinAdmin better alternate to phpmyadmin) is a full-featured database management tool written in PHP.<br>
http://www.adminer.org</p><br>
<strong>You need to know the root password from here /etc/yunohost/mysql or the app username and password from setting.yml under /etc/yunohost/apps/appname to login.</strong><br>
For themes download the adminer.css from the main website and put the file in the app folder.<br>
If you have problems with drivers see here: https://www.adminer.org/en/drivers.<br>


<h1>Why is Adminer better than phpMyAdmin?</h1>
<p>Replace phpMyAdmin with Adminer and you will get a tidier user interface, better support for MySQL features, higher performance and more security. See detailed comparison https://www.adminer.org/en/phpmyadmin/</p>
<p>Adminer development priorities are: 1. Security, 2. User experience, 3. Performance, 4. Feature set, 5. Size.</p>

# To-do
- [X] Installation and remove script.
- [X] Upgrade script
- [X] Backup and restore script.
- [ ] Check hash for source
- [ ] Option to add admin user access if the app is not piblic. 
