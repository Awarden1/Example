# PG6301 Eksamen Newspaper

[Heroku](https://pg6301-newspape.herokuapp.com/)
[Test rapport](https://github.com/kristiania-pg6301-2022/pgr6301-exam-Johannesn99/actions)

## Egenutfylling av funksjonelle krav
Jeg legger til kun krav som jeg selv fikk til.
* [ x ] Anonyme brukere skal se nyhetsaker når de kommer til nettsiden.
* [ x ] Når en ny sak publiseres, skal alle brukere få se den nye saken umiddelbart.
* [ x ] Brukere kan logge seg inn. For brukere, med google og får active directory, på skolens AD.
      * *Prøvde å lage med Google connect, men får av og til auth error.*
* [ x ] En bruker som er logget inn kan se på sin profilside.
      * *Samme gjelder her, får opp auth error* 
* [ x ] Brukere skal forbli pålogget når de refresher websiden.
* [ x ] En bruker som er logget inn kan klikke på en nyhetssak for å se detaljene om nyhetsaken.
* [ x ] "Redaksjonelle brukere" kan logge seg inn med Active Directory.
* [ x ] Redaksjonelle brukere kan publisere nyhetsartikler
* [ x ] Nyhetsartikkel skal inneholde en kategori.
      * *Bruker har muligheten til å legge til flere kategorier og liste dem ut i tillegg.*
* [ x ] En redaksjonell bruker skal kunne redigere en artikkel de selv har publisert

## Egenutfylling av tekniske krav
* [ x ] Github Actions
   * *Får ikke kjørt flere github actions da det står jeg ikke har flere tilgjengelig.*
* [ x ] Oppsett av package.json, parcel, express, prettier
* [ x ] React Router
* [ x ] Express app
* [ x ] Kommunikasjon mellom frontend (React) og backend (Express)
* [ x ] Deployment til Heroku
* [ x ] Bruk av MongoDB
* [ x ] OpenID Connect
    * *OpenID med Google Auth oppfører seg rar. I hele dag jeg har kodet så kunne jeg logge på med Google, men mot slutten så kom det feil med auth. Så jeg vil si den funker, men den er noe slapp så noen ganger så vil den ikke.*
[ x ] Web Sockets
[ x ] Jest med dokumentert testdekning

 ## Beskrivelse
Alt av kode som er blitt brukt her, har jeg lært fra forelesninger. 
Jeg har brukt pensum som "hjelpemiddel" under hele eksamen, og jeg har gått tilbake på 
forelesninger i tillegg. Det største hjelpemiddlet jeg brukte var mock exam som jeg hadde gjort fra før, 
og da kunne jeg på en måte bruke den som litt hjelp på denne eksamen, og det var min egen kode som jeg hadde
fått fra forelesning. I tillegg så har jeg prøvd å forklare kode med kommentarer underveis.
