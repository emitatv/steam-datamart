# 🎮 Steam — Datamart Interactivo & Dinámico

Dashboard interactivo y análisis multidimensional de datos de **15.000 videojuegos de Steam**, desarrollado con **Chart.js** y **Vanilla JavaScript**.

🌐 **Demo en vivo (GitHub Pages):** [https://emitatv.github.io/steam-datamart/](https://emitatv.github.io/steam-datamart/)

---

## 🚀 Características y Dinamismo

- **🎨 Fondo Interactivo con Partículas en Canvas:** Sistema de partículas reactivas al puntero del mouse, con constelaciones interconectadas y luces de nebulas ambientales.
- **📈 Odómetro Digital (Contadores Animados):** Conteo fluido y exponencial de las métricas clave (*Juegos visibles, Playtime promedio, Peak CCU, Precio medio y Metacritic*).
- **🕹️ Ficha Hero del Juego Seleccionado:** Al hacer clic en cualquier barra, punto del gráfico o fila de la tabla, se despliega una ficha con los datos del juego y resalte dorado en todos los gráficos.
- **⚡ Filtros Rápidos en 1 Clic:** Píldoras de filtrado instantáneo para *Top CCU*, *Free to Play*, *Metacritic ≥ 80*, *Más jugados*, y géneros principales.
- **📊 6 Gráficos Analíticos:**
  1. Top 10 — Average playtime forever
  2. Top 10 — Peak CCU
  3. Average playtime forever vs Peak CCU (Dispersión)
  4. Distribución de Metacritic score (Histograma)
  5. Metacritic score vs Average playtime forever (Dispersión)
  6. Géneros más frecuentes (Filtro interactivo)
- **📋 Explorador de Tabla:** Búsqueda en vivo, paginación configurable, tags de géneros clickeables y badges de clasificación de Metacritic.

---

## 📂 Estructura del Repositorio

```text
├── index.html                                        # Aplicación principal desplegada en GitHub Pages
├── steam_datamart_interactivo_final_v5_animaciones.html # Archivo original interactivo
├── datamart_steam.xlsx                               # Datamart fuente en Excel
├── Steam_Base_de_Datos_Normalizada.xlsx              # Base de datos normalizada
├── Steam_Base_de_Datos_Normalizada.pdf               # Documentación y diagramas
└── README.md                                         # Documentación del proyecto
```

---

## 🛠️ Tecnologías

- **HTML5 / CSS3** (Flexbox, CSS Grid, Glassmorphism, animaciones `@keyframes`).
- **JavaScript Moderno (ES6+)** (Canvas 2D API, Odómetro con `requestAnimationFrame`).
- **Chart.js** (Visualización interactiva y reactiva).
