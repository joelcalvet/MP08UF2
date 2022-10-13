# Activitat 3:

Per fer aquesta activitat comptem amb que **ja s'ha configurat el servei Owncloud a una Màquina Virtual** (MV).

**3.1.-** Llista els Virtual Hosts d'Apache per tal de veure si **owncloud.XYZ.com** està habilitat amb la comanda:

```
apache2ctl -S
``` 

**RESPOSTA**

![Selecció_126](https://user-images.githubusercontent.com/114162327/195623234-f5acc277-8201-4501-a9b8-fbd18ac662c5.png)

**3.2.-** A Owncloud podem veure que hi ha una serie de carpetes per defecte, mostra la ruta real a les tres carpetes dins de la teva MV.

![image](https://user-images.githubusercontent.com/110727546/194824543-c49bf482-ac93-432f-884c-d89487e587f3.png)


**RESPOSTA**

![Selecció_127](https://user-images.githubusercontent.com/114162327/195623546-eeba8ee1-ca0b-4d3c-9535-7a986daf9964.png)

**3.3.-** Al directori **Learn more about owncloud** hi ha informació en forma de fitxers pdf. Consulta'ls i respon aquestes preguntes:

- Quin són els tres tipus de protecció de dades que ofereix Owncloud?
 
Encryption in transit, encryption at rest and end-to-end encryption.

- Fes una petita descripció de cada un d'ells.

1. Encryption in transit: L'Owncloud porta HTTPS per defecte, té els protocols TLS més nous.
2. Encryption at rest: Els arxius es guarden al servidor d'Owncloud envés de guardar-los al disc dur per a tindre molta més seguretat, perquè utilitza una clau mestre.
3. End-to-end encryption: Per a assegurar-se de que ningú pugui accedir als arxius encriptats, l'Owncloud utilitza el end-to-end ja que és el nivell més alt de protecció de dades. 

- Per quina raó ens recomana utilitzar Owncloud per als documents de Microsoft Office de la nostra empresa?

Per a que els documents no es pugin perdre pràcticament de ninguna forma.

- Això passa a tots els països?

La Unió Europea té la regulació GDPR, que són unes regles de protecció de dades. Tots els països del món no utilitzen les mateixes regles, però són similars.

- Quina és la llicència d'OWncloud Enterprise?

Són unes caracteristiques d'Owncloud que et pots comprar a 12 € per usuari i mes.

- I la d'Owncloud Standard?

És el mateix que l'enterprise però només costa 5 € i no té llicencia comercial.

- Es poden veure videos en Streaming directament des de Owncloud?

Si que es pot veure.

- Es poden connectar directoris de Google Drive a Owncloud?

Es poden connectar.

- I Dropbox?

A Dropbox també.
https://owncloud.com/news/owncloud45-community/

- Compta Owncloud amb antivirus? En cas afirmatiu com es diu? 

Si, és una extensió que es diu Owncloud Anti-Virus extension. Ajuda proteigint del programari maliciós com troians o virus.

**3.4.-** Mostra els següents canvis de paràmetres d'usuari:

- Posa't una imatge d'usuari.
- Afegeix el teu mail de l'Institut.
- Canvia l'idioma a català.
- Mostra la versió d'Owncloud instal·lada.

**RESPOSTA**

![Selecció_128](https://user-images.githubusercontent.com/114162327/195662016-5005d087-b1e8-4b30-933d-33a46a69b508.png)

- Per a entrar a configuració es té que clicar a dalt a la dreta i ajustes.

![Selecció_130](https://user-images.githubusercontent.com/114162327/195661947-77171080-7456-40d8-92c9-3c68caf26b79.png)

- Per a penjar la foto es té que clicar la fletxeta i triar la imatge que vulguessim.
- Per a posar l'email simplement tenim que escriure'l i clicar al botó del costat
- Per a canviar l'idioma només el tenim que buscar i clicar-lo. 

![Selecció_131](https://user-images.githubusercontent.com/114162327/195662788-1a2b5010-0d75-47ce-a2a0-7f60d7c153a9.png)

- La versió surt a baix de tot de la pàgina de configuració. 




