# 🚀 NovaPlay Constructor (Cloud Forge)

<p align="center">
  <img src="https://raw.githubusercontent.com/novaplaygo/novaimg/main/novasplash.webp" width="120" alt="NovaPlay Logo">
</p>

> **La planta de ensamblaje en la nube para NovaPlay, NovaPanel y KillerPlay.**

---

## 🧐 ¿Qué es este repositorio?

Bienvenido a **Constructor**. ¿Te has preguntado por qué existe este lugar? Simple: mi computadora local es una pieza de museo arqueológica que sufre y llora cada vez que le pido abrir Android Studio y compilar Gradle. Si intentara compilar las tres aplicaciones aquí localmente, el ventilador despegaría como un cohete espacial y probablemente terminaría fundiendo la placa madre antes de ver un `BUILD SUCCESSFUL`.

Así que optamos por lo inteligente: delegar el trabajo pesado a la nube de GitHub Actions. ¡Porque las máquinas virtuales de Linux son jóvenes, rápidas, tienen fibra óptica y nunca se quejan del calor! ☁️🔥

---

## 🛠️ ¿Cómo funciona?

Este repositorio contiene los pipelines automáticos (*workflows*) para compilar, empaquetar y distribuir nuestras aplicaciones:

1. **NovaPlay** (`build-novaplay.yml`) — Compilación de la aplicación principal.
2. **NovaPanel** (`build-novapanel.yml`) — Compilación del panel de control administrativo.
3. **KillerPlay** (`build-killerplay.yml`) — Compilación de la aplicación de soporte.

Al finalizar cada compilación exitosa, el APK respectivo se sincroniza de forma automática y sin escalas al repositorio **[updater](https://github.com/NovaplayGO/updater)**. ¡Magia pura y cero estrés local! ✨

---

<p align="center">
  <i>Desarrollado con ❤️, código abierto y paciencia infinita por el equipo de NovaPlay.</i>
</p>
