# Local development wordpress

```
docker-compose up -d

open http://localhost:8080
```

Plugin
- WooCommerce
- WooCommerce -> activate

# deploy ubuntu

```
mysql_secure_installation
```

```
CREATE DATABASE wordpress CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
CREATE USER 'wpuser'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON wordpress.* TO 'wpuser'@'localhost';
```

```
wget https://wordpress.org/wordpress-6.4.2.tar.gz
tar zxf wordpress-6.4.2.tar.gz
```

#
