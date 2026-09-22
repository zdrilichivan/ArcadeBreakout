# 🕹️ Neon Breakout

Un classico **Breakout / Arkanoid** con rivestimento neon, in un singolo file HTML.

![stile](https://img.shields.io/badge/stile-neon--dark-00e5ff)
![dipendenze](https://img.shields.io/badge/dipendenze-0-ff2d95)
![vanilla](https://img.shields.io/badge/JS-vanilla-b6ff00)

## Gioca

Basta aprire `index.html` nel browser — nessun build, nessuna dipendenza, funziona anche offline.

- 🖱️ **Mouse** o `←` `→` / `A` `D` per muovere la racchetta
- ␣ **SPAZIO** (o clic) per lanciare la palla
- `P` / `ESC` per mettere in pausa
- `M` per mutare l'audio

## Caratteristiche

| | |
|---|---|
| **Punteggio** | con combo progressiva fino a ×8 |
| **Vite** | 3 iniziali, max 5 (power-up) |
| **Livelli** | 8 schemi progressivi, poi ciclo infinito con velocità e durezza crescenti |
| **Power-up** | Paddle+, Tempo lento, Multi-palla, +1 Vita |
| **Effetti** | particelle, anelli, scie, screen-shake, scanline CRT |
| **Audio** | effetti sintetizzati in Web Audio (niente file audio) |
| **Record** | salvato in `localStorage` |
| **Responsive** | anche touch su mobile |

## Struttura

Tutto in un file: HTML + CSS + JavaScript (canvas 2D, 60 fps, fisica a sub-step per evitare tunneling).

```
ArcadeBreakout/
├── index.html   # il gioco completo
└── README.md
```

Buon divertimento, e buonanotte al muro! 🧱💥
