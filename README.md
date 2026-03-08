# FerreMax-APP 🛠️

Una aplicación móvil moderna desarrollada con **Ionic 8** y **Angular 18**, diseñada para la gestión y visualización de productos de ferretería. Este proyecto demuestra el uso de tecnologías de vanguardia para crear experiencias multiplataforma (Web, Android, iOS) con un enfoque en el rendimiento y la mantenibilidad.

## 🚀 Tecnologías Principales

- **[Ionic Framework v8+](https://ionicframework.com/)**: El toolkit UI líder para construir aplicaciones móviles de alta calidad.
- **[Angular v18](https://angular.dev/)**: Framework de desarrollo web robusto, utilizando las últimas características como Signals, Standalone Components (preparado) y optimización de rendimiento.
- **[Capacitor v6](https://capacitorjs.com/)**: Puente nativo para acceder a funcionalidades de hardware y empaquetar la aplicación para tiendas.
- **[TypeScript](https://www.typescriptlang.org/)**: Tipado estático para un desarrollo más seguro y escalable.
- **SCSS**: Estilizado avanzado y modular.

## ✨ Características Destacadas

- **Navegación Fluida**: Menú lateral integrado con `ion-menu` para una experiencia de usuario intuitiva.
- **Arquitectura Limpia**: Estructura modular siguiendo las mejores prácticas de Angular.
- **Diseño Responsivo**: Adaptado tanto para dispositivos móviles como para navegadores web.
- **Optimización de Carga**: Uso de `PreloadAllModules` para una navegación instantánea entre páginas.

## 🛠️ Instalación y Configuración

Sigue estos pasos para ejecutar el proyecto localmente:

### Requisitos Previos
- Node.js (Versión recomendada LTS)
- Ionic CLI (`npm install -g @ionic/cli`)

### Pasos
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/FerreMax-APP.git
   ```
2. Instala las dependencias:
   ```bash
   npm install
   ```
3. Ejecuta la aplicación en modo desarrollo:
   ```bash
   ionic serve
   ```

## 📱 Compilación para Dispositivos

Para generar los recursos nativos y abrir en Android/iOS:

```bash
# Sincronizar con Capacitor
npx cap sync

# Abrir en Android Studio
npx cap open android

# Abrir en Xcode (iOS)
npx cap open ios
```

## 🧪 Calidad de Código

El proyecto incluye configuraciones estrictas para asegurar un código de alta calidad:
- **Linting**: ESLint configurado con reglas específicas para Angular.
- **Testing**: Suite de pruebas unitarias con Jasmine y Karma.

---

Este proyecto es una muestra de mis capacidades técnicas en el desarrollo móvil híbrido y frontend avanzado. ¡Espero que sea de tu interés! 😊
