# ☀️ AR Panel Solar — Gamificación y Estadísticas

> Experiencia de Realidad Aumentada para dar a conocer un sistema sostenible de **panel solar con atrapanieblas** a través de gamificación e visualización de estadísticas en 3D.

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Vuforia](https://img.shields.io/badge/Vuforia-RA-blue?style=flat-square)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)

---

## 📖 Descripción

Este proyecto presenta dos módulos de Realidad Aumentada que complementan una iniciativa sostenible: un sistema de **panel solar combinado con atrapanieblas** para recolección y distribución de agua. A través de la gamificación y visualización de datos en RA, se busca comunicar el impacto y funcionamiento del proyecto de forma interactiva.

---

## 🎮 Módulo 1 — Juego AR

Un minijuego de Realidad Aumentada donde el jugador interactúa con el panel solar en el mundo real.

### ¿Cómo funciona?

```
1. Apunta la cámara al marcador
        ↓
2. Aparece el panel solar en RA
        ↓
3. Caen elementos desde arriba:
   ☀️ Soles   → +puntos
   🔥 Fogatas → -puntos
        ↓
4. El jugador debe atrapar los soles y esquivar las fogatas
```

### Capturas — Juego AR

> Agrega tus capturas en `docs/images/game/` y reemplaza los enlaces.

| Marcador detectado | Gameplay | Puntuación |
|:-:|:-:|:-:|
| ![Marker](docs/images/game/marker.png) | ![Game](docs/images/game/gameplay.png) | ![Score](docs/images/game/score.png) |

🎥 **Video demo:** [Ver en YouTube](https://youtube.com/tu-link-juego)

---

## 📊 Módulo 2 — Estadísticas 3D en RA

Visualización de datos del proyecto mediante **gráficas de barras 3D** en Realidad Aumentada.

### ¿Cómo funciona?

```
1. Se carga un dataset con datos simulados del panel solar
        ↓
2. Apunta la cámara al marcador
        ↓
3. Aparecen gráficas de barras 3D en RA
        ↓
4. Se visualizan las estadísticas del proyecto
   (producción energética, agua recolectada, etc.)
```

### Capturas — Estadísticas AR

> Agrega tus capturas en `docs/images/stats/` y reemplaza los enlaces.

| Dataset cargado | Gráficas 3D | Vista general |
|:-:|:-:|:-:|
| ![Data](docs/images/stats/dataset.png) | ![Charts](docs/images/stats/charts3d.png) | ![Overview](docs/images/stats/overview.png) |

🎥 **Video demo:** [Ver en YouTube](https://youtube.com/tu-link-stats)

---

## 🛠️ Tecnologías

| Herramienta | Uso |
|---|---|
| **Unity** | Motor de desarrollo |
| **Vuforia** | Reconocimiento de marcadores y RA |
| **C#** | Lógica del juego y visualización |
| **Dataset CSV** | Datos simulados del panel solar |
| **Android** | Plataforma objetivo |

---

## 📋 Requisitos

- Unity 2021.x o superior
- Vuforia Engine SDK
- Android 8.0+ / iOS 12+
- Cámara trasera funcional

---

## 🚀 Instalación

```bash
# Clona el repositorio
git clone https://github.com/SebasGomez19/AR-PanelSolar.git

# Abre Unity Hub → Add → selecciona la carpeta del proyecto
# Espera que cargue la carpeta Library (se genera automáticamente)
```

---

## 📁 Estructura del proyecto

```
AR-PanelSolar/
├── Assets/
│   ├── Scenes/
│   │   ├── GameScene/       # Escena del minijuego
│   │   └── StatsScene/      # Escena de estadísticas
│   ├── Scripts/
│   │   ├── Game/            # Lógica del minijuego
│   │   └── Stats/           # Lógica de visualización
│   ├── Data/                # Dataset CSV
│   ├── Prefabs/
│   └── StreamingAssets/     # Base de datos Vuforia
├── Packages/
├── ProjectSettings/
└── docs/
    └── images/
        ├── game/            # Capturas del juego
        └── stats/           # Capturas de estadísticas
```

---

## 🌱 Contexto del proyecto

Este proyecto surge como herramienta de divulgación de una iniciativa sostenible que combina **energía solar** y **captación de agua mediante atrapanieblas**. La Realidad Aumentada permite comunicar de forma visual e interactiva tanto el funcionamiento del sistema como los datos recolectados.

---
| Módulo | Descarga |
|---|---|
| Juego AR | [Descargar APK](https://github.com/JulianaCorredorlopez/GAM-ARChicamocha/releases/download/v1.0/ARJuegoTimer.apk) |
| Estadísticas AR | [Descargar APK](https://github.com/JulianaCorredorlopez/GAM-ARChicamocha/releases/download/v1.0/stats-ar.apk) |
```

---

## 🖼️ Imágenes y marcadores
Estas sí van directo en el repo dentro de la carpeta `docs/images/`.

**Desde la web de GitHub:**
1. Entra al repo
2. Navega a `docs/images/game/` (si no existe, la creas)
3. **Add file → Upload files**
4. Sube tus screenshots, fotos y el marcador
5. Commit ✅

**Estructura recomendada:**
```
docs/
└── images/
    ├── marker.png          ← imagen del marcador para imprimir
    ├── game/
    │   ├── gameplay.png
    │   └── score.png
    └── stats/
        ├── charts3d.png
        └── overview.png


<div align="center">
<sub>Desarrollado por <a href="https://github.comJulianaCorredorlopez">Juliana Andrea Corredor Lopez</a></sub>
</div>
