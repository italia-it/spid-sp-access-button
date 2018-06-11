# SPID - Sistema Pubblico di Identità Digitale
## Pulsante INPS per richiesta SPID

### Componenti
Per gestire l’accesso ai servizi pubblici e privati che utilizzano il sistema SPID, si rende necessario, sia per una questione di user experience che di immagine del sistema, la standardizzazione delle interfacce, della comunicazione e dell’utilizzo del logo SPID.


### SPID Sp Access Button
Il pulsante è disponibile in 4 dimensioni (s / m / l / xl) ed in formato “get” (chiamata ad una pagina esterna) e “post” (form interna al pulsante). I diversi IDP sono mostrati in ordine random attraverso una piccola funzione javascript che potrebbe essere sostituita attraverso una procedura di randomizzazione lato server.
La pagina di accesso dovrà essere "mobile first" e utilizzabile su ogni tipologia di dispositivo.

Il pulsante è disponibile nella versione da utilizzare in produzione (production) e nella versione da utilizzare in sviluppo (development).

Il sistema richiede Jquery 1.8+.


### Struttura del file system
```
spid-sp-access-button/
│
├── src/
│   ├── spid-sp-access-button.html
│   ├── css
│   │   ├── spid-sp-access-button.min.css
│   ├── img
│   │   ├── spid-ico-circle-bb.png
│   │   ├── spid-ico-circle-bb.svg
│   │   ├── spid-idp-arubaid.png
│   │   ├── spid-idp-arubaid.svg
│   │   ├── spid-idp-infocertid.png
│   │   ├── spid-idp-infocertid.svg
│   │   ├── spid-idp-intesaid.png
│   │   ├── spid-idp-intesaid.svg
│   │   ├── spid-idp-namirialid.png
│   │   ├── spid-idp-namirialid.svg
│   │   ├── spid-idp-posteid.png
│   │   ├── spid-idp-posteid.svg
│   │   ├── spid-idp-sielteid.png
│   │   ├── spid-idp-sielteid.svg
│   │   ├── spid-idp-spiditalia.png
│   │   ├── spid-idp-spiditalia.svg
│   │   ├── spid-idp-timid.png
│   │   ├── spid-idp-timid.svg
│   ├── js
│   │   ├── jquery.min.js
│   │   ├── spid-sp-access-button.min.js
```

### Aggiornamenti

#### v1.0 (11/06/2018)


### Metadata IDP SPID

#### Metadata INPS


#### Metadata IDP SPID Aderenti
