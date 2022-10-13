# Instal·lació de l'Owncloud
## Guia de instal·lació:
## Requeriments:
-Linux: Ubuntu 22.04 LTS

-Servidor web: Apache

-Base de dades: MariaDB

-PHP (versió 7.3 o 7.4)

## Instal·lació:

![Selecció_067](https://user-images.githubusercontent.com/114162327/193092486-3b7aa5b8-735c-4afa-b0e8-9904a4b0b74a.png)

Primer instalem l'apache.

![Selecció_068](https://user-images.githubusercontent.com/114162327/193092595-e13864b5-ce03-42c2-8f5c-b7b50b4a5678.png)

Desactivem el llistat de directoris del servidor.

![Selecció_069](https://user-images.githubusercontent.com/114162327/193092760-799815e1-ead0-4771-869a-1cebf74e68b9.png)

Instalem el MariaDB.

![Selecció_070](https://user-images.githubusercontent.com/114162327/193092849-b1903eff-47c0-4020-9bd9-1e4a4aa10ec7.png)

Configurem la instal·ació.

![Selecció_071](https://user-images.githubusercontent.com/114162327/193095580-59385ecf-ba85-4e1b-b70a-ba452498e16c.png)

Reiniciem el servidor MariaDB.

![Selecció_072](https://user-images.githubusercontent.com/114162327/193095985-ade702c2-ee12-473b-83b2-537aa9ab6023.png)

Entrem al servidor.

![Selecció_083](https://user-images.githubusercontent.com/114162327/193096933-8ab075fd-ab2a-4287-9902-fbc23e23651b.png)

Creem la base de dades.

![Selecció_073](https://user-images.githubusercontent.com/114162327/193096185-d4e79df6-600b-4e1a-904f-8a33b317d4f2.png)

Creem un usuari i la seva contrasenya.

![Selecció_074](https://user-images.githubusercontent.com/114162327/193097755-d9253679-0761-46fe-9909-683cf75b30c3.png)

Li donem accés a l'usuari per a la base de dades creada anteriorment.

![Selecció_075](https://user-images.githubusercontent.com/114162327/193098407-e9dd7408-cc89-4d89-ae42-43097d75a509.png)
![Selecció_076](https://user-images.githubusercontent.com/114162327/193098438-68bf165c-c39c-4c00-a62e-01d210cddda8.png)

Instalem PHP.

![Selecció_077](https://user-images.githubusercontent.com/114162327/193098849-764bbaa2-6a56-4819-8bcf-1c6439cb64c2.png)

Actualitzem els repositoris.

![Selecció_078](https://user-images.githubusercontent.com/114162327/193099018-15f6a0cd-f2f0-4e97-b9c6-fdaa6c46a2a0.png)

Instalem els mòduls necessaris.

![Selecció_079](https://user-images.githubusercontent.com/114162327/193099308-64b91c9c-00d1-4132-a37d-cf17aecf66a3.png)

Editem el fitxer php.ni.

![Selecció_080](https://user-images.githubusercontent.com/114162327/193099557-caccf031-ee04-421b-89d3-e97c21980418.png)

Canviem els valors del fitxer.

![Selecció_084](https://user-images.githubusercontent.com/114162327/193101556-ef13b44c-8474-41d3-891c-47615c3357ca.png)
![Selecció_085](https://user-images.githubusercontent.com/114162327/193101653-8d9a182f-3d25-4c8d-b2f3-91007fa4e459.png)
![Selecció_086](https://user-images.githubusercontent.com/114162327/193101690-0387e087-a01c-421f-a49e-30df4e0e3674.png)

Descarguem la última versió d'Owncloud, descomprimim els fitxers i deplacem els arxius a "/var/www/html/owncloud".

![Selecció_081](https://user-images.githubusercontent.com/114162327/193103327-6adfe8d4-b2fe-4b36-b9a8-a0a9700b4275.png)
![Selecció_082](https://user-images.githubusercontent.com/114162327/193103348-b9fd402c-80bd-446a-89ea-fc7f1afde21e.png)

Canviem el propietari i permisos dels directoris d'Owncloud. www-data per a que Apache els pugui utilitzar, 755 per a que els pugui executar i llegir qualsevol usuari.

![Selecció_087](https://user-images.githubusercontent.com/114162327/193104637-564984ef-ceea-4997-ac55-159d42d68843.png)

Finalment escrivim localhost/owncloud al nevagador i posem usuari i contrasenya.

![Selecció_088](https://user-images.githubusercontent.com/114162327/193105137-381daa86-5664-401e-a14d-a8218e3f218b.png)

(No es veu com executo les comandes perquè no he fet captures quan les executava)

Ara instal·leu Owncloud seguint el tutorial.

Expliqueu com fer la instal·lació pas a pas.

El nom de domini vostre serà owncloud.XYZ.com on XYZ són les vostres inicials.

![Selecció_133](https://user-images.githubusercontent.com/114162327/195667029-5ba298ea-7a87-4b84-bc53-06aa436540b8.png)

Entrem al fitxer de configuració de l'Owncloud.

![Selecció_132](https://user-images.githubusercontent.com/114162327/195667601-de229981-a981-4a51-bcb1-c0a4210de16a.png)

Aquí canviem el nom i alias del servidor i afegim tot el que hi ha a baix.

![Selecció_134](https://user-images.githubusercontent.com/114162327/195668697-0b0fc215-8619-4636-bc0d-8c886b96942b.png)

Habilito Owncloud i el mode rewrite.

![Selecció_135](https://user-images.githubusercontent.com/114162327/195668809-3a807a71-97e5-473e-995a-ac51d2446eba.png)

Reinicio el servidor per a que es guardin tots els canvis.

![Selecció_136](https://user-images.githubusercontent.com/114162327/195668908-33e7118b-0567-482d-90c3-a9c16e1202eb.png)

Editem aquest fitxer de configuració.

![Selecció_137](https://user-images.githubusercontent.com/114162327/195669017-ea0381ee-cb96-443f-85bd-30a1893858e1.png)

Es té que posar owncloud.(les inicials).com

Expliqueu:

- Què signifiquen a Apache les línies de configuració del fitxer owncloud.conf.

![](https://dungeonofbits.com/images/owncloud1.jpg)

- L'identificador de l'admin.
- El lloc a on l'owncloud està instal·lat
- El nom del servidor
- L'alias del servidor per si se busca en www. davant.
- Un alias per a dir que /owncloud és el mateix que /var/www/html/owncloud.
- El directori a on està situat l'Owncloud.
- FollowSymLinks és un enllaç simbolic, el que fa aquesta linia es activar-los.
- Serveix per a facilitar la realització de canvis en la configuració, fa que els fitxers .htaccess funcionin.
- Desactiva el dav.
- Fa que la pàgina principal sigui /var/www/html/owncloud
- És un missatge d'error

- Què fa la comanda a2ensite?

Habilita el lloc web.

- I la comanda a2dissite?

Dishabilita el lloc web.

- Què significa la línia de /etc/hosts 
  - 127.0.0.1 owncloud.XYZ.com
  - Serveix per a fer una relació entre la ip i la direcció
