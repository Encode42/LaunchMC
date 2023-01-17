[Website]: https://flags.sh
[Website Badge]: https://img.shields.io/badge/Website-202b38?labelColor=202b38&logo=html5&logoColor=white&style=flat-square
[Support]: https://encode42.dev/support
[Support Badge]: https://img.shields.io/discord/646517284453613578?color=7289da&labelColor=7289da&label=​&logo=discord&logoColor=white&style=flat-square
[Codacy]: https://app.codacy.com/gh/Encode42/flags.sh/dashboard
[Codacy Badge]: https://img.shields.io/codacy/grade/fcab733f761c4c09a0216f89feb95797?color=172B4D&labelColor=172B4D&label=​&logo=codacy&style=flat-square
[Weblate]: https://hosted.weblate.org/projects/flags-sh/
[Weblate Badge]: https://img.shields.io/weblate/progress/flags-sh?server=https%3A%2F%2Fhosted.weblate.org&color=2ECCAA&labelColor=2ECCAA&logo=weblate&logoColor=white&label=​&style=flat-square

<img src=".github/assets/badge.svg" align="left">

<div align="right">

# flags.sh
### A simple script generator to start your Minecraft servers with optimal flags.

[![][Website Badge]][Website] [![][Support Badge]][Support]  
[![][Codacy Badge]][Codacy] [![][Weblate Badge]][Weblate]
</div>

Includes many configuration options such as Aikar's flags, automatic restarting, and Pterodactyl container overhead calculation.

Inspired by [startmc.sh](https://startmc.sh), and built with [qwik](https://qwik.builder.io).

This is the `qwik` branch, which is a rewrite from scratch using modern technologies and better design philosophies. As such, it is missing many essential features from the current production version.

### 🔨  Building
Ensure [pnpm](https://pnpm.io) and [Node.js](https://nodejs.org) are installed.

1. Enter the directory containing the flags.sh source code in your terminal.
2. Install the build dependencies via `pnpm install`.
3. Start a live development environment and make your changes.
  - `pnpm run dev`: Start a live development environment
4. Ensure your changes work in a production environment.
  - `pnpm run build`: Build for production
  - `pnpm run deploy`: Deploy an example Cloudflare Pages environment

### 🌐  Translating
Translations are provided by [Weblate]. Any and all translations are welcome!
