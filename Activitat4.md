# Activitat 4:

## Gestió d'usuaris:

Hi ha dos tipus d'usuaris, els admins amb permissos per gestionar Owncloud i els usuaris normals.

On fica resposta afegeix una captura de pantalla on es vegi que has fet l'acció que es demana.

**Aquesta part de la pràctica la feu amb un company/a, li creeu un usuari i li doneu el vostre nom de domini d'Owncloud.**

Per a que pugui accedir necessitarà:

- La MV amb owncloud ha d'estar en mode "adaptador pont".
- El fitxer /etc/hosts del company ha de tenir la IP de la MV i el nom de domini de la MV del company/a.


**4.1.-** Crea un usuari admin que es digui adminXYZ, on XYZ són les inicials del teu nom:

**RESPOSTA**

![Selecció_159](https://user-images.githubusercontent.com/114162327/198062257-51217314-490a-45db-8c2a-e951aecaeba6.png)

**4.2.-** Inicia sessió com a l'usuari adminXYZ.

**RESPOSTA**

![Selecció_161](https://user-images.githubusercontent.com/114162327/198062395-69d62c69-9fed-4631-adbd-9c0d98af033f.png)

**4.3.-** Crea un usuari XYZ on XYZ son les inicials del company/a i afegeix-lo al grup usuaris, aquest usuari tindrà una quota de 512 MB.

**RESPOSTA**

![Selecció_162](https://user-images.githubusercontent.com/114162327/198062446-fb4e3063-497f-4694-8cdb-adfaee85c54a.png)

**4.4.-** Podem crear fitxers d'una mida determinada a Linux amb la comanda:

```
truncate -s 10M file.txt
```

A l'exemple es crea un fitxer de 10MB.

Crea 6 fitxers de 100MB i pujal's a Owncloud un per un.

**RESPOSTA**

**4.5.-** Mostra el missatge d'error per haver superat la quota d'usuari.

**RESPOSTA**

![Selecció_164](https://user-images.githubusercontent.com/114162327/198062614-7fcb7751-65a7-4883-8c6b-a309146b3fa2.png)

**4.6.-** Busca al teu perfil quin percentatge de quota estas utilitzant.

**RESPOSTA**

![Selecció_165](https://user-images.githubusercontent.com/114162327/198063135-d43797ef-596f-470e-b692-602f79aa480f.png)

**4.7.-** Canvia la quota de l'usuari a 1GB i mostra tots els fitxers pujats.

**RESPOSTA**

![Selecció_166](https://user-images.githubusercontent.com/114162327/198063320-ef4e7d23-d95e-48d3-a278-bee4a2ecfa9c.png)

**4.8.-** Crea un usuari anomenat usuari2XYZ i fical al grup usuaris.

**RESPOSTA**

![Selecció_182](https://user-images.githubusercontent.com/114162327/198066582-b8dc168c-abb0-47ae-b2c4-207052514743.png)

**4.9.-** Comparteix un fitxer de usuariXYZ a usuari2XYZ i mostra com l'usuari2XYZ pot veure i descarregar el fitxer.

**RESPOSTA**

![Selecció_183](https://user-images.githubusercontent.com/114162327/198067370-ff6980b6-126a-4292-a99e-16f650c6a145.png)

![Selecció_184](https://user-images.githubusercontent.com/114162327/198069023-be901b90-5b13-4c66-a62b-bfd2285cc096.png)


**4.10.-** Esborra la carpeta Learn more about owncloud.

**RESPOSTA**

![Selecció_186](https://user-images.githubusercontent.com/114162327/198069838-64efc1a7-f10a-4e31-8633-31e11b47c91c.png)

Per a esborrar-lo es té que clicar a eliminar.

**4.11.-** Recupera la carpeta Learn more about owncloud.

**RESPOSTA**

![Selecció_185](https://user-images.githubusercontent.com/114162327/198069528-69241583-e052-42ae-9ec6-4dd4fa66da1d.png)

Es té que clicar a recuperar per a restaurar-lo.

**4.12.-** Com a usuariXYZ crea una carpeta nova anomenada shared i comparteix-la amb l'usuari usuari2XYZ.

**RESPOSTA**

![Selecció_187](https://user-images.githubusercontent.com/114162327/198071510-df312109-4864-4d94-846e-72033ca7961f.png)

![Selecció_188](https://user-images.githubusercontent.com/114162327/198071558-30d596a1-0ac2-46a1-a55d-23c02ba08860.png)

**4.13.-** Entra a Market instal·la dues aplicacions que no estiguin ja instal·lades i explica què fan i com funcionen.

![image](https://user-images.githubusercontent.com/110727546/196159706-705ff624-c409-4632-acb4-f43ffcc486d4.png)

**RESPOSTA PRIMERA APP**

**RESPOSTA SEGONA APP**

**4.14.-** Crearem una carpeta nova per emmagatzematge a Owncloud, la carpeta serà /media/publicXYZ on XYZ són les teves inicials i apareixerà amb el nom de public als usuaris.

Aquesta carpeta haurà de pertànyer a l'usuari www-data.

**RESPOSTA**

**4.15.-** Connectarem la carpeta publicXYZ com emmagatzematge local, tal i com s'indica [aquí](https://doc.owncloud.com/server/next/admin_manual/configuration/files/external_storage/local.html). Tots els usuaris tindran accés a la carpeta.

**RESPOSTA**

**4.16.-** Un usuari normal pujarà un fitxer a la carpeta public.

**RESPOSTA**

**OPCIONAL.-** Aquesta tasca és opcional.

Intenta connectar com a emmagatzematge extern el teu compte de Google Drive de l'Institut. Tens com fer-ho [aquí](https://doc.owncloud.com/server/next/admin_manual/configuration/files/external_storage/google.html).
