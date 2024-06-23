<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Pico YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/pico.svg)](https://dash.yunohost.org/appci/app/pico) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/pico.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/pico.maintain.svg)

[![Instalatu Pico YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pico)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Pico YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Pico is a stupidly simple, blazing fast, flat file CMS. That’s definitely a mouthful, what does it even mean? In the most basic sense, it means that there is no administration backend or database to deal with. You simply create markdown files in the content folder and those files become your pages. There’s much more to Pico than that though.

**Paketatutako bertsioa:** 3.0.0~ynh2

## Pantaila-argazkiak

![Pico(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://picocms.org/>
- Administratzaileen dokumentazio ofiziala: <https://picocms.org/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/picocms/Pico>
- YunoHost Denda: <https://apps.yunohost.org/app/pico>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/pico_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/pico_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pico_ynh/tree/testing --debug
edo
sudo yunohost app upgrade pico -u https://github.com/YunoHost-Apps/pico_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
