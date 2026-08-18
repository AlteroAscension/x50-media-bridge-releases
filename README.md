# X50 Media Bridge releases

Public binary releases and Magisk update metadata for X50 Media Bridge.

This repository intentionally contains no application source code. X50 Media
Bridge does not require a licence or runtime activation.

## LSPosed: required scope

After installing or updating the module, open **LSPosed → Modules → X50 Media
Bridge → Scope** and enable exactly these three packages:

- `ru.mark99.carapp` — **LunarisApp**;
- `ecarx.xsf.mediacenter` — **NSMediaCenter**;
- `com.neusoft.carplay` — **AppleCarPlay**.

Do not select Yandex Navigator, AutoKit/Carlinkit, or the Media Bridge package
itself. They are media sources, not hook targets. Restart the head unit after
changing LSPosed scope.

Magisk update metadata:

`https://raw.githubusercontent.com/AlteroAscension/x50-media-bridge-releases/main/media/update.json`
