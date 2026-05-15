<img width="1086" height="1448" alt="Banner QR" src="https://github.com/user-attachments/assets/de2f58c1-de7d-47a0-a94e-aab9419c271a" />



<div align="center">

<img src="https://raw.githubusercontent.com/coderhouse2025-droid/MichiPlay/main/Maat_Astronauta.png" width="160" alt="Maat Astronauta">

# 🐱🚀 Maat Astronauta

**Videojuego arcade espacial · HTML5 · Un solo archivo · Sin instalación**
<img width="1536" height="1024" alt="file_00000000a98471f5b7c6cb9473ef3ad1" src="https://github.com/user-attachments/assets/b6311cfc-dba1-4cf5-9478-2d11397b028d" />


[![Jugar ahora](https://img.shields.io/badge/🎮_JUGAR_AHORA-020818?style=for-the-badge&logo=rocket&logoColor=22d3ee)](https://coderhouse2025-droid.github.io/MichiPlay/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas_API-22d3ee?style=for-the-badge)](https://developer.mozilla.org/es/docs/Web/API/Canvas_API)

</div>

---

## 🌌 Sobre el juego

**Maat** es una gata astronauta perdida en el cosmos. Ayudala a recolectar **ovillos de lana** dispersos en plataformas espaciales, esquivando a los bichos alienígenas que patrullan cada órbita. Cuando complete su misión, una nave espacial aterrizará para llevarla de regreso a las estrellas.

> *Una aventura de plataformas arcade en un único archivo HTML, sin frameworks, sin instalación, jugable desde cualquier dispositivo.*

---

## 🎮 Cómo jugar

| Acción | Teclado | Celular |
|--------|---------|---------|
| Moverse | `←` `→` | Botones ◀ ▶ |
| Saltar | `↑` o `Espacio` | Botón ↑ |
| Música | Botón 🔊 | Botón 🔊 |
| Salir | Botón Exit | Botón Exit |

**Objetivo:** recolectar **12 🧶 ovillos** antes de que los bichos te atrapen. Tenés **3 vidas** 🐾.

---

## 🌠 Niveles

Cada nivel tiene una paleta de color y dificultad creciente:

| # | Nombre | Color | Enemigos |
|---|--------|-------|----------|
| 1 | Órbita 1 | 🩵 Cian | 2 |
| 2 | Luna | 💜 Morado | 3 |
| 3 | Asteroide | 🧡 Naranja | 4 |
| 4 | Nebulosa | 💚 Verde | 5 |
| 5 | Abismo | 💛 Dorado | 6 |

---

## 🏁 Secuencia final

Al completar los 12 ovillos se activa la cinemática de victoria:

```
🚀 La nave desciende hasta el suelo
🐱 Maat camina y sube a bordo
🔥 Ignición — los motores se encienden
⬆️  Despegue acelerado hacia las estrellas
✨ Aparece: MICHI MISIÓN CUMPLIDA
```

---

## 🛠️ Tecnologías

```
HTML5 Canvas API    →  renderizado completo del juego (sin imágenes para sprites)
Web Audio API       →  efectos de sonido sintetizados en tiempo real
Screen Orientation  →  bloqueo automático a horizontal en mobile
CSS Custom Props    →  sistema de temas por nivel (5 paletas)
Open Graph / OG     →  preview atractivo al compartir el link
Google Fonts        →  Orbitron (arcade) + Exo 2 (UI)
```

---

## 📁 Estructura del repositorio

```
MichiPlay/
├── index.html               ← el juego completo (un solo archivo)
├── Maat_Astronauta.png      ← imagen hero (portada y Open Graph)
├── README.md                ← este archivo
└── Sonidos/
    ├── Musica-espacial.mp3
    ├── MIAU.mp3
    └── rocket_launch.mp3
```

---

## 📱 Mobile

- ✅ Controles táctiles minimalistas (no tapan la pantalla)
- ✅ Gira automáticamente a modo horizontal al iniciar
- ✅ Aviso visual si el teléfono está en vertical
- ✅ Escala proporcional a cualquier tamaño de pantalla
- ✅ Preview del link en WhatsApp, Twitter, Discord, Telegram

---

## 🎨 Características técnicas destacadas

- **Sin dependencias** — cero npm, cero frameworks, cero instalación
- **Sprite procedural** — Maat dibujada 100% con Canvas (elipses, arcos, bézier)
- **Audio procedural** — sonidos de salto, daño y colección sintetizados con osciladores
- **Física propia** — gravedad, aceleración, fricción y colisiones AABB implementadas desde cero
- **Sistema de partículas** — estrellas fugaces, partículas de colisión, humo del cohete
- **Efecto scanline CSS** — estética CRT retro sobre toda la pantalla

---

## 🚀 Cómo ejecutar

**Opción 1 — Directamente en el navegador:**
```
https://coderhouse2025-droid.github.io/MichiPlay/

```
# 👤 Autor

Juan Manuel Orellana
---


                                                         *"Una michi aventura espacial hecha con amor 🐾✨"*

</div>
