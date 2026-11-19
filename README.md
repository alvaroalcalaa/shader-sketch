# Shader Sketch

> A tiny generative-art playground built with raw WebGL.

[Español](#español) · [English](#english) · [MIT](LICENSE)

## Español

**Shader Sketch** es un microestudio creativo para experimentar con shaders generativos en tiempo real. Ajusta el color, el ritmo y la complejidad desde el navegador; no utiliza framework, dependencias ni backend.

### Qué incluye

- Tres escenas procedurales: **Aurora**, **Topography** y **Orbit**.
- Controles de paleta, velocidad y densidad.
- Render WebGL en pantalla completa y botón para pausar.
- Exportación de la composición actual como PNG.
- Diseño responsive y compatible con controles táctiles.

### Stack

HTML, CSS, JavaScript y WebGL 1.0. No requiere instalación.

### Cómo ejecutarlo

```bash
git clone https://github.com/alvaroalcalaa/shader-sketch.git
cd shader-sketch
python -m http.server 8000
```

Abre [http://localhost:8000](http://localhost:8000) y prueba los presets. También puede abrirse `index.html` directamente en la mayoría de navegadores.

### Estructura

```text
├── index.html   # Interfaz y controles
├── app.js       # WebGL, shaders y exportación
├── styles.css   # Diseño responsive
└── LICENSE      # MIT
```

### Demo

Selecciona **Topography**, sube *Density* y pulsa **Export PNG**: tendrás una textura procedural lista para una miniatura, un fondo o una pieza de concept art.

---

## English

**Shader Sketch** is a compact creative lab for real-time generative shaders. Tune color, motion and complexity in the browser, with no framework, dependencies or backend.

### Features

- Three procedural scenes: **Aurora**, **Topography** and **Orbit**.
- Palette, speed and density controls.
- Full-screen WebGL rendering with pause control.
- Export the current composition as PNG.
- Responsive UI with touch-friendly controls.

### Run it

```bash
git clone https://github.com/alvaroalcalaa/shader-sketch.git
cd shader-sketch
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000), pick a preset and explore.

## License

Released under the [MIT License](LICENSE).
