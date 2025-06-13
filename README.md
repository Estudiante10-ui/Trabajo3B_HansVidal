# PetTracker

Aplicación móvil desarrollada con Ionic y Angular.

## Descripción

Este proyecto corresponde a la cáscara de navegación de la aplicación **PetTracker**, diseñada en el marco de la asignatura. La app incluye estructura de navegación entre páginas mediante un menú lateral. Actualmente no contiene lógica funcional ni contenidos reales, solo navegación y maquetación básica.

## Desarrollado por

**Hans Vidal**

## 🧱 Estructura del Proyecto

El proyecto contiene las siguientes páginas:

- Home
- Login
- Registro
- Perfil
- Mascota
- Alertas
- Rastraer

## Instrucciones de Instalación

1. descarga este repositorio y accede a la carpeta del proyecto:

    cd Trabajo3B_HansVidal

2. Instala las dependencias necesarias:

    npm install

3. Ejecuta la aplicación en el navegador:

    ionic serve

⚠️ Asegúrate de tener instalado Ionic CLI. Si no lo tienes:

    npm install -g @ionic/cli


## Problemas enfrentados

Se detectaron errores en los módulos generados automáticamente (duplicación de carpetas como home/home, conflictos con standalone).
Ajustes en app-routing.module.ts y organización de carpetas para lograr rutas limpias.
El menú lateral no se cerraba automáticamente; se resolvió agregando menuClose en cada enlace.
Dificultad al centrar la app en el navegador: finalmente se utilizó el modo móvil del navegador (F12 > Responsive).

## Herramientas utilizadas

Ionic CLI: v7.x
Angular: v19.x
Node.js: v22.x
NPM: v10.x

## Observaciones

El menú lateral es visible en todas las páginas y funciona correctamente.
La aplicación puede ser visualizada correctamente como versión móvil usando herramientas del navegador (modo desarrollador).
El contenido de cada página aún está vacío, pues esta versión representa la estructura básica de navegación.
