# Instal·lar Wordpress

## Instal·lem LAMP

```
sudo apt update
sudo apt install apache2 mariadb-server php
```

## Descarreguem wordpress i el descomprimim

```
wget https://es.wordpress.org/latest-es_ES.tar.gz
tar -xzvf latest-es_ES.tar.gz
```

## Creem un directori per a Wordpress

```
sudo mkdir /var/www/html/smx
mv ./wordpress/* /var/www/html/smx
chown -R www-data:www-data /var/www/html/smx
```

## Preparar la base de dades

```
sudo mariadb
```

```
CREATE USER 'delegado'@'localhost' IDENTIFIED BY 'shrek';
CREATE DATABASE smixers;
GRANT ALL PRIVILEGES ON smixers.* TO 'delegado'@'localhost';
FLUSH PRIVILEGES;
```

## Entrem a Wordpress

Obrim el navegador i escrivim **localhost**

<img width="1166" height="787" alt="image" src="https://github.com/user-attachments/assets/cba38ab8-0e9c-43c0-a89e-bc7c09d81280" />

<img width="1028" height="791" alt="image" src="https://github.com/user-attachments/assets/cccc6658-5d90-4a70-a355-c738ea89af57" />

<img width="1041" height="379" alt="image" src="https://github.com/user-attachments/assets/756c0adb-a4a1-4478-bbd8-d60f11f47f87" />

<img width="810" height="824" alt="image" src="https://github.com/user-attachments/assets/3cea2fa0-ea61-412e-8d2b-0e868ece3995" />

<img width="782" height="830" alt="image" src="https://github.com/user-attachments/assets/058af607-0112-46d0-a453-a16a78bb5d3f" />

<img width="1919" height="829" alt="image" src="https://github.com/user-attachments/assets/05e91db7-8b1f-4082-bbce-a961b34dd4e9" />
