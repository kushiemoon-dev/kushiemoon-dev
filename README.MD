<!--
    ██╗  ██╗██╗   ██╗███████╗██╗  ██╗██╗███████╗
    ██║ ██╔╝██║   ██║██╔════╝██║  ██║██║██╔════╝
    █████╔╝ ██║   ██║███████╗███████║██║█████╗
    ██╔═██╗ ██║   ██║╚════██║██╔══██║██║██╔══╝
    ██║  ██╗╚██████╔╝███████║██║  ██║██║███████╗
    ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝╚══════╝
-->

<div align="center">

<!-- CUSTOM SVG HEADER WITH GLITCH EFFECT -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Scanline pattern -->
    <pattern id="scanlines" patternUnits="userSpaceOnUse" width="100%" height="4">
      <rect width="100%" height="2" fill="rgba(168, 85, 247, 0.03)"/>
      <rect y="2" width="100%" height="2" fill="transparent"/>
    </pattern>
    <!-- Glitch filter -->
    <filter id="glitch">
      <feColorMatrix type="matrix" values="1 0 0 0 0  0 0.8 0.2 0 0  0 0.2 0.8 0 0  0 0 0 1 0"/>
    </filter>
    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="#0d1117"/>

  <!-- Grid lines -->
  <g stroke="rgba(124, 58, 237, 0.1)" stroke-width="1">
    <line x1="0" y1="50" x2="800" y2="50"/>
    <line x1="0" y1="100" x2="800" y2="100"/>
    <line x1="0" y1="150" x2="800" y2="150"/>
    <line x1="200" y1="0" x2="200" y2="200"/>
    <line x1="400" y1="0" x2="400" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
  </g>

  <!-- Scanlines overlay -->
  <rect width="100%" height="100%" fill="url(#scanlines)"/>

  <!-- Main text -->
  <text x="400" y="90" font-family="monospace" font-size="56" font-weight="bold" fill="#a855f7" text-anchor="middle" filter="url(#glow)">
    KUSHIE
  </text>

  <!-- Subtitle -->
  <text x="400" y="130" font-family="monospace" font-size="14" fill="#9ca3af" text-anchor="middle" letter-spacing="4">
    FULL-STACK DEV // RETRO TECH // FLAC HOARDER
  </text>

  <!-- Decorative elements -->
  <text x="30" y="30" font-family="monospace" font-size="10" fill="#7c3aed">[ SYSTEM ONLINE ]</text>
  <text x="650" y="30" font-family="monospace" font-size="10" fill="#4ade80">STATUS: ACTIVE</text>
  <text x="30" y="180" font-family="monospace" font-size="10" fill="#6b7280">v3.0.1</text>
  <text x="680" y="180" font-family="monospace" font-size="10" fill="#6b7280">NORMANDY//FR</text>

  <!-- Corner brackets -->
  <path d="M 10 10 L 10 40 M 10 10 L 40 10" stroke="#a855f7" stroke-width="2" fill="none"/>
  <path d="M 790 10 L 790 40 M 790 10 L 760 10" stroke="#a855f7" stroke-width="2" fill="none"/>
  <path d="M 10 190 L 10 160 M 10 190 L 40 190" stroke="#a855f7" stroke-width="2" fill="none"/>
  <path d="M 790 190 L 790 160 M 790 190 L 760 190" stroke="#a855f7" stroke-width="2" fill="none"/>

  <!-- Animated pulse circle -->
  <circle cx="750" cy="25" r="4" fill="#4ade80">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                                                                              │
│   > Building desktop apps, web platforms, and modding vintage hardware.      │
│   > Currently obsessed with Go + Wails and Rust + Tauri for native apps.     │
│                                                                              │
│   Location: France                                                           │
│   Status: Open to interesting projects                                       │
│   Pronouns: she/her                                                          │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

<br/>

## `// TECH_STACK`

<table>
<tr>
<td width="33%" valign="top">

### <img src="https://img.shields.io/badge/backend-7c3aed?style=flat-square" height="20"/>

<p>
<img src="https://img.shields.io/badge/Go-0d1117?style=flat-square&logo=go&logoColor=a855f7" alt="Go"/>
<img src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=a855f7" alt="Rust"/>
<img src="https://img.shields.io/badge/Symfony_7-0d1117?style=flat-square&logo=symfony&logoColor=a855f7" alt="Symfony"/>
<img src="https://img.shields.io/badge/PHP-0d1117?style=flat-square&logo=php&logoColor=a855f7" alt="PHP"/>
<img src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=a855f7" alt="Node.js"/>
<img src="https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=a855f7" alt="MySQL"/>
</p>

</td>
<td width="33%" valign="top">

### <img src="https://img.shields.io/badge/frontend-a855f7?style=flat-square" height="20"/>

<p>
<img src="https://img.shields.io/badge/SvelteKit-0d1117?style=flat-square&logo=svelte&logoColor=a855f7" alt="SvelteKit"/>
<img src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=a855f7" alt="React"/>
<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=a855f7" alt="Next.js"/>
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=a855f7" alt="TypeScript"/>
<img src="https://img.shields.io/badge/TailwindCSS-0d1117?style=flat-square&logo=tailwindcss&logoColor=a855f7" alt="TailwindCSS"/>
</p>

</td>
<td width="33%" valign="top">

### <img src="https://img.shields.io/badge/desktop_&_infra-c4b5fd?style=flat-square&logoColor=0d1117" height="20"/>

<p>
<img src="https://img.shields.io/badge/Wails-0d1117?style=flat-square&logo=go&logoColor=a855f7" alt="Wails"/>
<img src="https://img.shields.io/badge/Tauri_2-0d1117?style=flat-square&logo=tauri&logoColor=a855f7" alt="Tauri"/>
<img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=a855f7" alt="Docker"/>
<img src="https://img.shields.io/badge/Proxmox-0d1117?style=flat-square&logo=proxmox&logoColor=a855f7" alt="Proxmox"/>
<img src="https://img.shields.io/badge/Arch_Linux-0d1117?style=flat-square&logo=archlinux&logoColor=a855f7" alt="Arch"/>
</p>

</td>
</tr>
</table>

<br/>

## `// FEATURED_PROJECTS`

<table>
<tr>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/♫_FLACIDAL-7c3aed?style=for-the-badge&logoColor=white" alt="FLACidal"/>

<br/><br/>

```
╔══════════════════════════╗
║  Tidal & Qobuz → FLAC    ║
║  HI_RES 24-bit lossless  ║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/Go-0d1117?style=flat-square&logo=go&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Wails-0d1117?style=flat-square&logo=webassembly&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Svelte-0d1117?style=flat-square&logo=svelte&logoColor=a855f7"/>

<br/><br/>

[![Repo](https://img.shields.io/badge/→_Repo-a855f7?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/KushieMoon-dev/flacidal)

</td>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/♫_YOUFLAC-a855f7?style=for-the-badge&logoColor=white" alt="YouFlac"/>

<br/><br/>

```
╔══════════════════════════╗
║  YouTube 4K video        ║
║  + FLAC audio → MKV      ║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/Go-0d1117?style=flat-square&logo=go&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Wails-0d1117?style=flat-square&logo=webassembly&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=a855f7"/>

<br/><br/>

[![Repo](https://img.shields.io/badge/→_Repo-a855f7?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/KushieMoon-dev/youflac)

</td>
</tr>
<tr>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/▶_OPENDROP-7c3aed?style=for-the-badge&logoColor=white" alt="OpenDrop"/>

<br/><br/>

```
╔══════════════════════════╗
║  Multi-deck VJ app       ║
║  MilkDrop • ProjectM     ║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Tauri_2-0d1117?style=flat-square&logo=tauri&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Svelte_5-0d1117?style=flat-square&logo=svelte&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/OpenGL-0d1117?style=flat-square&logo=opengl&logoColor=a855f7"/>

<br/><br/>

[![Repo](https://img.shields.io/badge/→_Repo-a855f7?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/KushieMoon-dev/OpenDrop)

</td>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/◈_KUSHIE.DEV-c4b5fd?style=for-the-badge&logoColor=0d1117" alt="Portfolio"/>

<br/><br/>

```
╔══════════════════════════╗
║  Portfolio • i18n        ║
║  FR/EN/DE • Lighthouse 90+║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/SvelteKit-0d1117?style=flat-square&logo=svelte&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/TailwindCSS-0d1117?style=flat-square&logo=tailwindcss&logoColor=a855f7"/>

<br/><br/>

[![Site](https://img.shields.io/badge/→_Live-a855f7?style=flat-square&logo=firefox&logoColor=white)](https://kushie.dev)
[![Repo](https://img.shields.io/badge/→_Repo-7c3aed?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/KushieMoon-dev/kushie.dev)

</td>
</tr>
<tr>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/🎳_BC_BAYEUX-a855f7?style=for-the-badge&logoColor=white" alt="Bowling Club"/>

<br/><br/>

```
╔══════════════════════════╗
║  Club management app     ║
║  Events • Scores • Stats ║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/Symfony_7.3-0d1117?style=flat-square&logo=symfony&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/Chart.js-0d1117?style=flat-square&logo=chartdotjs&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=a855f7"/>

<br/><br/>

<sub>Client project • Private repo</sub>

</td>
<td width="50%" align="center">

<img src="https://img.shields.io/badge/🦋_CHRYSALIDE-c4b5fd?style=for-the-badge&logoColor=0d1117" alt="Chrysalide"/>

<br/><br/>

```
╔══════════════════════════╗
║  Trans health tracker    ║
║  100% local • IndexedDB  ║
╚══════════════════════════╝
```

<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/PWA-0d1117?style=flat-square&logo=pwa&logoColor=a855f7"/>
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=a855f7"/>

<br/><br/>

[![Repo](https://img.shields.io/badge/→_Repo-a855f7?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/KushieMoon-dev/chrysalide)

</td>
</tr>
</table>

<br/>

## `// RETRO_CORNER`

<div align="center">

```
╭───────────────────────────────────────────────────────────────────╮
│                     ~ vintage tech collector ~                    │
╰───────────────────────────────────────────────────────────────────╯
```

### `consoles/`

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/iPod_Classic_5.5G-7c3aed?style=for-the-badge&logo=apple&logoColor=white"/>
<br/><sub>Rockbox • 256GB flash<br/>2000mAh • U2 edition</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Nintendo_3DS-a855f7?style=for-the-badge&logo=nintendo3ds&logoColor=white"/>
<br/><sub>Luma3DS CFW</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/DS_Lite-c4b5fd?style=for-the-badge&logo=nintendo&logoColor=0d1117"/>
<br/><sub>R4 Gold</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/PlayStation_1-7c3aed?style=for-the-badge&logo=playstation&logoColor=white"/>
<br/><sub>OG Sony</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Nintendo_64-a855f7?style=for-the-badge&logo=nintendo&logoColor=white"/>
<br/><sub>64-bit era</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Wii-c4b5fd?style=for-the-badge&logo=wii&logoColor=0d1117"/>
<br/><sub>Modded • Homebrew</sub>
</td>
</tr>
</table>

### `audio_video/`

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/Technics_HiFi-7c3aed?style=for-the-badge&logo=sony&logoColor=white"/>
<br/><sub>Vintage sound system</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/CRT_80cm-a855f7?style=for-the-badge&logo=samsung&logoColor=white"/>
<br/><sub>Trans Continent<br/>The real display</sub>
</td>
</tr>
</table>

### `homelab/`

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/Proxmox_Cluster-7c3aed?style=for-the-badge&logo=proxmox&logoColor=white"/>
<br/><sub>Triple node • 2005/2010 hardware<br/>Old machines, new tricks</sub>
</td>
</tr>
</table>

### `philosophy/`

```
┌─────────────────────────────────────────────────────────────┐
│  Next goal: ditch the smartphone, embrace the flipphone     │
│  Less screen time, more real life                           │
└─────────────────────────────────────────────────────────────┘
```

</div>

<br/>

## `// CONNECT`

<div align="center">

```
┌──────────────────────────────────────┐
│         let's build something        │
└──────────────────────────────────────┘
```

<a href="https://kushie.dev/contact">
<img src="https://img.shields.io/badge/Portfolio-7c3aed?style=for-the-badge&logo=firefox&logoColor=white"/>
</a>
&nbsp;
<a href="https://discord.gg/kushiemoon">
<img src="https://img.shields.io/badge/Discord-a855f7?style=for-the-badge&logo=discord&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:kushie.dev@icloud.com">
<img src="https://img.shields.io/badge/Email-c4b5fd?style=for-the-badge&logo=maildotru&logoColor=0d1117"/>
</a>

<br/><br/>

<a href="https://codeberg.org/KushieMoon-dev">
<img src="https://img.shields.io/badge/Codeberg-0d1117?style=flat-square&logo=codeberg&logoColor=a855f7"/>
</a>
&nbsp;
<a href="https://github.com/kushiemoon-dev">
<img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=a855f7"/>
</a>

</div>

<br/>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║                          Thanks for stopping by!                             ║
║                                                                              ║
║           "The best code is free. The second best is readable code."         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<sub>Last updated: January 2026 • Made with insomnia and mass amounts of tea</sub>

</div>
