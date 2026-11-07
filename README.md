# MCManager

Gestor de servidores de Minecraft para uso personal · *Personal Minecraft server manager*

> **Proyecto personal y sin fines de lucro.** No se vende, no tiene anuncios, no cobra suscripciones ni donaciones y no se distribuye al público. Lo uso solo para jugar con un grupo pequeño de amigos.

## ¿Qué es?

Una app de escritorio para Windows (Electron + React) que uso para crear y administrar mis propios servidores de Minecraft. Mis amigos se conectan a través de Radmin VPN.

## Funciones

- Crear servidores Vanilla, Fabric, Forge y Paper.
- Consola en tiempo real y editor de `server.properties`.
- Buscar e instalar mods, plugins y modpacks desde **Modrinth** y **CurseForge**.
- Abrir Radmin VPN automáticamente y mostrar la IP para que entren mis amigos.

## Cómo usa la API de CurseForge

- Solo para **buscar** mods y modpacks e **instalarlos en mi propio servidor**.
- **Respeta la decisión de cada autor:** si un mod no permite la distribución por terceros, la app no lo descarga; muestra el enlace a su página oficial en CurseForge para descargarlo manualmente.
- Para los modpacks usa el **Server Pack oficial** que publica el autor, cuando existe.
- **No vuelve a publicar ni redistribuye** archivos de CurseForge: cada descarga va directo a la carpeta del servidor en mi PC.
- Indica en la interfaz de qué plataforma viene cada mod (Modrinth o CurseForge) y enlaza a su página original.
- Uso de bajo volumen: un solo usuario, algunas búsquedas e instalaciones de vez en cuando.
- La API key se guarda solo en mi PC y no se incluye en el código.

---

### English summary

MCManager is a **personal, non-commercial** desktop app for running Minecraft servers to play with a few friends. It is not sold, has no ads, subscriptions or donations, and is not distributed publicly.

The CurseForge API is used only to search for mods and modpacks and install them on my own server. The app respects each author's distribution setting: files that don't allow third-party distribution are never downloaded. Instead, the app links to the official CurseForge page. It prefers official server packs, never re-hosts or redistributes CurseForge files, shows where each mod comes from with a link to its original page, and makes a low volume of requests from a single user. The API key is stored locally and is not committed to the code.
