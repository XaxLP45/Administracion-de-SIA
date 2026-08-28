# SIAO Zulia - Sistema Comunal

Sistema de Información Automatizado para Consejos Comunales en el Estado Zulia.

---

## 🚀 ¿Por qué no abre haciendo doble clic directo en `index.html`?

Este proyecto está construido con **React 19 + TypeScript + Vite**. 
Los navegadores web no pueden ejecutar archivos `.tsx` (TypeScript/JSX) directamente desde el disco (`file:///`) por políticas de seguridad del navegador y porque requieren ser procesados por Vite o empaquetados previamente.

---

## 🛠️ Cómo iniciar y abrir la aplicación en tu computadora

### Opción 1: En modo desarrollo (Recomendado)

1. Abre una terminal (PowerShell, CMD, Bash o Terminal de VS Code) en la carpeta del proyecto.
2. Instala las dependencias:
   ```bash
   npm install
   ```
3. Inicia el servidor local de desarrollo:
   ```bash
   npm run dev
   ```
4. Abre en tu navegador el enlace que aparece en la consola (usualmente **`http://localhost:3000`** o **`http://localhost:5173`**).

---

### Opción 2: Compilar para producción (Archivos estáticos en `/dist`)

Si deseas generar los archivos listos para publicar o servir:

1. Ejecuta:
   ```bash
   npm run build
   ```
2. Para probar la versión compilada en tu navegador:
   ```bash
   npm run preview
   ```
   o bien usando cualquier servidor web estático:
   ```bash
   npx serve dist
   ```
