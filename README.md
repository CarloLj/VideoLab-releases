# VideoLab

Local Twitch alerts with OBS overlays and a visual scene editor. Runs on your own
PC and talks only to Twitch — no StreamElements, no Streamlabs, no account on any
third-party service.

*Alertas de Twitch locales, con overlays para OBS y editor visual de escenas.
Corre en tu propio PC y solo habla con Twitch.*

## Download / Descargar

**[→ Latest release / Última versión](https://github.com/CarloLj/VideoLab-releases/releases/latest)**

Grab `VideoLab-Setup-<version>.exe` and run it.

- Nothing else to install: Node.js is bundled.
- No administrator rights: it installs just for your user.
- Windows 10 or later, 64-bit.

It is not code-signed yet, so Windows may show **"Windows protected your PC"**.
Click **More info → Run anyway**.

*No necesitas instalar nada más (Node.js va incluido) ni permisos de
administrador. Si Windows muestra "Windows protegió tu PC", pulsa **Más
información → Ejecutar de todas formas**.*

## First run / Primer arranque

A setup wizard walks you through 4 steps. The first one is **turning on
two-factor authentication (2FA)** on your Twitch account: without it, Twitch will
not let you create the application VideoLab needs.

Your credentials stay on your computer. They are never sent anywhere.

*Un asistente te guía en 4 pasos. El primero es **activar la verificación en dos
pasos (2FA)** en tu cuenta de Twitch: sin eso Twitch no deja crear la aplicación
que VideoLab necesita. Tus credenciales se quedan en tu equipo.*

## What it does / Qué hace

- Alerts for follows, subs, resubs, gifted subs, bits, raids and channel point
  redemptions — plus chat and channel goals.
- Browser-source overlays for OBS, one URL per scene.
- Visual editor: drag elements onto a 1920×1080 canvas, with themes, custom
  fonts, your own sounds and GIFs per event type.
- Live event log, so you can tell real events from tests at a glance.
- Automatic update check, with one-click install.

## Updates / Actualizaciones

VideoLab tells you when a new version is out and installs it in one click from
the Panel. Each installer ships its SHA256 as an attached file, which VideoLab
verifies automatically before installing.

*VideoLab avisa cuando hay versión nueva y la instala con un clic desde el Panel.
Cada instalador trae su SHA256 y se comprueba solo antes de instalar.*

## About this repo / Sobre este repo

Downloads only. The source code lives in a separate repository.

*Solo las descargas. El código fuente está en otro repositorio.*
