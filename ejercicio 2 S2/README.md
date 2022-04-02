# ITA-S2
Curso de IT Academy React
Sprint 2 Ejercicio 

> si se utilia el comando npm install, en las dependencias está la instalación de sass, también bootstrap.

> npm install -g sass para instalar sass a nivel de sistema operativo

> En visual studio code se puede descargar la extensión 
Live Sass compiler (Live Sass Compiler v3.0.0 Ritwick Dey 2.066.281 (203)) 
Compile Sass or Scss to CSS at realtime with live browser reload
Sirve para compilar automáticamente ante cada cambio en el archivo scss.



El teu repte és construir una landing page i fer que sembli el més a prop possible del disseny:

Nivell 1
- Exercici 1
En aquest exercici començarem per la part principal, que és el contingut que els usuaris en entrar en la web:
-images-

Per a això hauràs d'implementar:

- La barra de navegació superior fixa, usant el component "navBar" de Bootstrap.

- El contingut principal, usant el grid responsive que proporciona Bootstrap per a dividir la pantalla en dues columnes, a l'esquerra com pots veure està l'eslògan, la descripció i els botons, i en la columna dreta la imatge.


Important: En aquest link tens les imatges que necessitaràs per a desenvolupar la web.

Ajuda:  Abans de començar a muntar la web, hauràs de veure el vídeo recomanat anteriorment, per a aprendre a instal·lar Bootstrap en el teu projecte usant el gestor de paquets npm.



Requisits mínims: 

- Instal·lar Boostrap en el projecte, no usar cdn (que és càrrega mitjançant per link, com per exemple "<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/...." rel="stylesheet" crossorigin="anonymous">").

- Usar component navBar de Boostrap.

- Usar Grid Responsive de Bootstrap, ja que s'ha de veure bé en tauleta i mòbil.

- Modificar amb SASS, mitjançant l'arxiu creat per tu "main.scss", el color principal i secundari de Boostrap. Usa aquestes variables per al color dels botons

Color principal: #5265E1
Color secundari: #FA5959. 


- Exercici 2
Ara toca crear la part de funcionalitats del producte que estem venent:
-images-

Requisits mínims:

- L'apartat "Features", amb el text descriptiu, ha d'anar dins del Grid de Boostrap.

- Has d'usar el component tabs de Boostrap, customizando els seus estils per a adaptar-los a la nostra web (en aquest tutorial ensenya com fer-ho).

- Responsive.



- Exercici 3
Construirem la tercera part de la web: l'àrea de descàrregues:

-images-

Com les cards de la imatge són molt diferents a les cards de Boostrap, en aquest exercici de donem la possibilitat de bé customizar les cards de Boostrap o crear les teves pròpies classes per maquetar-les.

Requisits mínims:

- Responsive.

- Botons de Bootstrap de color primary definit en l'exercici 1.


- Exercici 4
Enhorabona! ja gairebé tens el nivell 1 completat! Ara toca desenvolupar l'apartat de FAQS:

-images-

Requisits mínims

- Usar el component "Accordion" i customizar les classes per a adaptar-lo al disseny.

- Responsive.

- Botó de Boostrap.

-----------------------------------------------

Nivell 2

Compte, abans de passar al nivell 2 verifica que has entès bé tots els exercicis del nivell 1. 

El nivell 2 i 3 són opcionals, l'important és aprendre els conceptes de cada sprint, si l'has copiat ràpid d'internet no té valor, ja que si passes així tots els sprints, hauràs treballat molt i après poc. 

En una entrevista tècnica en una empresa o en les proves de nivell de l'itinerari (després del sprint 5 i 9) es detecta molt ràpid aquests casos. No retardis el teu aprenentatge, millor fer pocs exercicis bé que molts ràpids.

- Exercici 5
Només falta un bloc per a temrinar la web: el footer.

Requisits mínims

- Usar els formularis de Bootstrap

- Mostrar un missatge d'error quan el formulari del butlletí de notícies s'envia, si el camp d'entrada és buit o l'adreça de correu electrònic no està formatada correctament ( s'ha de fer amb Bootstrap, més informació de com validar formularis amb Boostrap  aquí).

--------------------------------------------------

Nivell 3
- Exercici 6
Modificar els estats actius dels botons, links, tabs i avisos de la web, perquè quedin així quan es passi el cursor per sobre:


- Exercici 7

Com has implementat el posicionament de les cards de descàrregues de l'exercici 3? has creat una classe o id per a cada card?:




Per a pocs elements no suposa molta feina, però que passaria si tinguessis una web plena de cards,  les quals vols estilitzar en funció de la seva posició?, hauries de crear massa classes!!.


En aquest exercici hauràs de posicionar les targetes de l'exercici 3 usant l'herència de SASS conjuntament amb la pseudo-classe nth-child (en aquest cas podem usar nth-child(1), nth-child(2) i nth-child(3) per a simplificar l'exercici).