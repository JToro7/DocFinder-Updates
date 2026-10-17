# DocFinder-Updates — Repositorio Oficial de Lanzamientos y Actualizaciones

Este repositorio público aloja los paquetes instaladores, binarios portables y manifiestos de actualización para **DocFinder Windows**.

---

## 📦 Último Lanzamiento

- **Versión:** `0.1.0`
- **Fecha:** `2026-10-17`
- **Arquitectura:** Windows 64-bit (Windows 10 / Windows 11)
- **Instalador / Paquete Portable:** [Descargar DocFinder-v0.1.0-Windows-x64.zip](https://github.com/JToro7/DocFinder-Updates/releases/download/v0.1.0/DocFinder-v0.1.0-Windows-x64.zip)
- **Hash SHA-256:** `41739414985b59d1e3e00c90c773aa4326a243dc6f37bc9cb7a6c8eeb1dd95ab`

---

## 🚀 Cómo se publican las actualizaciones

Las actualizaciones se construyen de forma automatizada mediante **GitHub Actions** en el repositorio principal de DocFinder y se publican automáticamente en las [Releases de este repositorio](https://github.com/JToro7/DocFinder-Updates/releases).

El archivo [`version.json`](./version.json) en la rama principal actúa como manifiesto para que la aplicación de escritorio consulte y verifique si existe una nueva versión disponible sin sufrir restricciones de cuota de API.
