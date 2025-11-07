# 🔗 Nivell 4 – Mestres de la Sincronització

**Objectiu:** sincronitzar una carpeta local amb el teu OwnCloud.

**Reptes:**

1. Instal·la el client d’OwnCloud a la teva màquina virtual (10 XP)

Obre el terminal.
Afegeix el repositori i instal·la el client:

```
sudo apt update
sudo apt install owncloud-client -y
```

Després de la instal·lació, pots obrir-lo des del menú d’aplicacions (busca ownCloud Desktop Client).

2. Connecta’l amb el teu servidor (10 XP)

Quan s’obri, et demanarà una adreça del servidor → escriu:

http://IP_DEL_SERVIDOR/owncloud


(exemple: http://192.168.56.10/owncloud)

Introdueix el teu usuari i contrasenya d’OwnCloud.

Tria una carpeta local on es guardaran els fitxers sincronitzats, per exemple:

/home/usuari/Sincronitzats


Accepta i deixa que es faci la primera sincronització.

🧩 3. Prova la sincronització

A l’aplicació web d’OwnCloud (des del navegador), crea un fitxer:

Nom: README_sync.txt

Contingut: “Aquest fitxer s’ha creat des del núvol.”

Espera uns segons: el fitxer hauria d’aparèixer automàticament a la carpeta local /Sincronitzats.

Ara edita’l localment i afegeix una línia:

Editat des de la màquina local.


Després de guardar, comprova des de la web que el fitxer s’ha actualitzat.
👉 Això confirma que la sincronització bidireccional funciona.

🎯 Extra XP

Compartir una carpeta amb enllaç públic:

A la web d’OwnCloud, crea una carpeta “Compartit”.

Clica la icona de compartició (tres punts o símbol de compartir).

Activa l’opció “Enllaç públic” i afegeix una contrasenya.

Copia l’enllaç per comprovar que pots accedir-hi des d’un altre navegador o màquina.
