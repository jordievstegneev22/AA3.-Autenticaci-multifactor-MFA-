# NF1AA3. Autenticació multifactor (MFA)

**Mòdul:** 0226 Seguretat Informàtica (SMX)

📄 **Activitat feta:** [Guia: activar l'autenticació multifactor (MFA) al compte de Google](guia-mfa.md)

---

## Presentació de l'activitat

L'accés a aplicacions i serveis informàtics, tant corporatius com personals, requereix un procés d'autenticació. Aquest procés consisteix en verificar que l'usuari és qui diu ser. Tradicionalment, aquest procés es realitza amb un nom d'usuari i una contrasenya. Malauradament, les contrasenyes són fàcilment vulnerables a atacs de força bruta, phishing o altres tècniques de robatori d'identitat.

Per aquest motiu, és recomanable utilitzar un sistema d'autenticació multifactor (MFA), que combina diversos factors d'autenticació per augmentar la seguretat. Així, es pot combinar una contrasenya amb un token físic o una característica biomètrica. És el mateix sistema que per exemple, estem acostumats a utilitzar als caixers automàtics, combinem un objecte físic, la targeta, amb una contrasenya, en aquest cas el PIN.

L’ús d’aquests sistemes multifactor en sistemes o aplicacions informàtiques, fins ara tenia l’inconvenient que era complicat i car que els usuaris poguessin utilitzar un segon factor físic o biomètric. La popularització dels smartphones ha canviat això radicalment, ja que ens permet utilitzar el mòbil com sistema d’autenticació en diverses formes: via SMS (és un mètode força insegur), usant apps d’autenticació o amb propostes com FIDO.

Ara us toca a vosaltres guiar a una organització client per tal que pugui configurar els seus comptes amb autenticació multifactor. Necessiten una guia clara i concisa que els permeti configurar els seus comptes amb aquest sistema de seguretat.

## Durada de l'activitat

Durada aproximada (fer a casa): 1 hora

## Objectius de l'activitat

Reconèixer la necessitat d’utilitzar autenticació multifactor per augmentar la seguretat en el procés d’autenticació.

## Competències treballades

- **j)** Elaborar documentació tècnica i administrativa del sistema, complint les normes i reglamentació del sector, per al seu manteniment i l’assistència al client.
- **l)** Assessorar i assistir al client, canalitzant a un nivell superior els supòsits que ho requereixin per trobar solucions adequades a les necessitats d’aquest.
- **n)** Mantenir un esperit constant d’innovació i actualització en l’àmbit del sector informàtic.

## Resultats d'aprenentatge i criteris d'avaluació

**RA1.** Aplica mesures de seguretat passiva en sistemes informàtics descrivint característiques d'entorns i relacionant-les amb les seves necessitats.

- 1.1 Valora la importància de mantenir la informació segura.
- 1.8 Valora la importància d'establir una política de contrasenyes.

## Continguts

Seguretat lògica: gestió de contrasenyes

## Capacitats clau

- Autonomia
- Organització del treball
- Responsabilitat

---

## Enunciat de l'activitat

Les aplicacions d'autenticació, són una de les opcions que més s'ha popularitzat per la seva facilitat d'ús. El mecanisme és senzill, per una banda hem de configurar el servei d’Internet o local per tal de treballar amb aquest segon factor, per l’altra, cal instal·lar al mòbil l’app (Microsoft i Google tenen apps, però n’hi ha de forces més opcions) i procedir a vincular els serveis.

Com a prova de concepte d’aquesta tecnologia anem a configurar un compte de G-Suite per tal que funcioni amb aquest doble factor.

### Entorn de treball

- Ordinador amb connexió a Internet.
- Smartphone Android o iOS.

### Instruccions de l'activitat

El primer pas serà instal·lar l’app d’autenticació, per aquest exercici usarem Google Authenticator, però funcionaria exactament igual amb qualsevol altra. Trobareu l’app a la botiga d’aplicacions bé sigui d’Android o d’iOS.

A continuació, anirem a la configuració del nostre compte del domini mataro.epiaedu.cat a la pestanya de seguretat i a Inici de sessió a Google.

Entrarem a Verificació en dos passos i allà seguirem l’assistent. En primer lloc us farà vincular el mòbil amb el compte (és el mètode principal que utilitza Google). Un cop configurat, us permet seleccionar un segon mètode que pot ser codis per imprimir (ideal per quan no tens opció d’usar el mòbil), una aplicació d’autenticació o fins i tot claus físiques de seguretat. Aquí és on heu de triar aplicació Authenticator.

Quan seleccionem l’opció d’autenticació, ens apareixerà per pantalla un codi QR que haurem d’escanejar amb l’aplicació d’autenticació. Un cop fet, demanarà que introduïm el codi de 6 dígits que apareix a l’aplicació per confirmar (compte que va variant!).

> 💡 **Recomanació:** els codis de seguretat d'un sol ús, són molt útils quan no teniu cobertura o accés al mòbil. Veureu qque quan ho seleccioneu us genera 10 codis que podeu imprimir o descarregar i guardar a un lloc segur.

Un cop ho teniu configurat, quan es vol iniciar sessió, per defecte us dona l'opció d'usar el mòbil, però si trieu l'opció "Provar una altra manera", podreu seleccionar l'aplicació d'autenticació i introduir el codi que us genera l'app.

## Documentació i Informe Final

Elabora una guia pensada perquè els usuaris de la teva organització puguin configurar el seu compte amb autenticació multifactor. La guia ha de ser clara i concisa, amb captures de pantalla i instruccions pas a pas.

## Enllaços d'interès

- Kaspersky. *La autentificación de doble factor en SMS es insegura, ¿qué alternativas hay?*
