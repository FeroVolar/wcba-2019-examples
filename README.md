# wcba-2019-examples
WordCamp Bratislava 2019 - Docker pre každého
---

## Prezentácia
https://speakerdeck.com/alian/docker-pre-kazdeho


## Demo
Naklonovanie repozitára so submodulom Twenty Twenty

`git clone --recursive https://github.com/FeroVolar/wcba-2019-examples`

- adresár `demo-1` - vytvorenie WP a DB kontajnera
- adresár `demo-2` - vytvorenie WP, DB a phpMyAdmin kontajnera

## Užitočné príkazy

Vytvorenie kontajnerov

`docker-compose up -d`

Stopnutie kontajnerov

`docker-compose stop`

Spustenie kontajnerov

`docker-compose start`

Zrušenie kontajnerov aj volume

`docker-compose down -v`
