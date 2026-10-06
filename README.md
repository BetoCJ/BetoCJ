<div align="center">

<img src="logo.png" alt="Mapucraft" width="150">

# Hola, soy Alberto 👋

**Estudiante · Desarrollador y administrador de [Mapucraft](https://mapucraft.com)**
Universidad del Bío-Bío (UBB) · Chile 🇨🇱

[![Mapucraft](https://img.shields.io/badge/Mapucraft-mapucraft.com-DE8E16?style=for-the-badge&logo=minecraft&logoColor=white)](https://mapucraft.com)
[![Discord](https://img.shields.io/badge/Discord-Comunidad-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/YDJKpgEU3m)
[![Wiki](https://img.shields.io/badge/Wiki-Mapucraft-0F0C05?style=for-the-badge&logo=gitbook&logoColor=white)](https://mapu-1.gitbook.io/mapucraft)

</div>

---

## 🧭 Sobre mí

- 🎮 Creo y administro **Mapucraft**, un servidor de Minecraft chileno con identidad mapuche (Towny, economía y comunidad; Java y Bedrock).
- 🛠️ Me encargo de todo el ecosistema: **servidor, bot de Discord, tienda, web de sanciones, wiki y web del servidor**, y de que hablen entre sí de forma segura.
- 📚 Estudio en la **Universidad del Bío-Bío** y publico aquí mis laboratorios y proyectos.
- 🔐 Me importa la seguridad: firmas HMAC entre servicios, límites de peticiones, antispam (Turnstile) y secretos fuera del código.

## 🧩 El ecosistema Mapucraft

```mermaid
flowchart LR
    J([Jugadores]) --> MC[Servidor Minecraft<br/>Towny · Paper]
    J --> T[Tienda web<br/>mapucraft.com]
    J --> W[Web del servidor<br/>ciudades · rankings · soporte]
    J --> C[Web de castigos<br/>apelaciones]
    MC <--> B{{Bot de Discord<br/>Python}}
    B -- datos públicos firmados --> W
    C -- apelaciones --> B
    T -- compras --> B
    B <--> D([Discord])
    WK[Wiki GitBook] --- D
```

| Pieza | Qué hace | Tecnología |
|---|---|---|
| 🤖 **Bot de Discord** | Tickets, apelaciones, niveles, ciudades de Towny, compras → roles, monitoreo de caídas, calendario | Python · discord.py · MySQL · SQLite |
| 🌐 **Web del servidor** | Ciudades, naciones, rankings, calendario, soporte y panel de staff con login de Discord | PHP 8 · OAuth2 · HMAC · Cloudflare Turnstile |
| 🔨 **Web de castigos** | Historial de sanciones (LiteBans) y apelaciones con código de seguimiento | PHP · MySQL |
| 🛒 **Tienda** | Rangos, llaves y MapuPoints con entrega automática | Node.js · Tebex |
| 📖 **Wiki** | Guías de Towny, economía, eventos y dungeons | GitBook · Markdown |
| ⚙️ **Servidor de juego** | Plugins a medida, Skript, MythicMobs, Oraxen, DiscordSRV | Java · Skript · YAML |

## 🧰 Tecnologías

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Discord](https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Minecraft](https://img.shields.io/badge/Minecraft-62B47A?style=flat-square&logo=minecraft&logoColor=white)

## 📌 Proyectos públicos

| Repositorio | Descripción |
|---|---|
| [**mapu-wiki**](https://github.com/BetoCJ/mapu-wiki) | Wiki oficial de Mapucraft: Towny, economía, eventos y dungeons. |
| [**agenda-demo**](https://github.com/BetoCJ/agenda-demo) | Agenda de gestión (demo con datos ficticios): tareas por cliente y planta. |
| [**Labs-Tasks**](https://github.com/BetoCJ/Labs-Tasks) | Laboratorios y tareas de la carrera. |

> Los repositorios del bot, la tienda y la web de sanciones son privados porque incluyen la operación del servidor.

## 📊 GitHub

<div align="center">

![Estadísticas](https://github-readme-stats.vercel.app/api?username=BetoCJ&show_icons=true&theme=transparent&hide_border=true&title_color=DE8E16&icon_color=DE8E16&text_color=9e9e9e)
![Lenguajes](https://github-readme-stats.vercel.app/api/top-langs/?username=BetoCJ&layout=compact&theme=transparent&hide_border=true&title_color=DE8E16&text_color=9e9e9e)

</div>

## 📫 Contacto

- 🎮 Sígueme en el juego: **`mapucraft.com`** (Java) · Bedrock `185.73.243.22:19132`
- 💬 Discord de la comunidad: <https://discord.gg/YDJKpgEU3m>
- 🛒 Tienda: <https://mapucraft.com> · 📖 Wiki: <https://mapu-1.gitbook.io/mapucraft>

<div align="center"><sub>Hecho con ☕ y mucho Minecraft · Chaltu may 💛</sub></div>
