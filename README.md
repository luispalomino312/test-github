# test-github
# Proyecto DevOps & Project Management Fundamentals

Este repositorio ha sido creado como parte del trabajo final del curso **DevOps & Project Management Fundamentals**. El objetivo es implementar un flujo de trabajo DevOps utilizando GitHub, con Integración Continua (CI), un enfoque colaborativo basado en GitHub Flow.

---

## 📌 Objetivos del Proyecto

- Aplicar prácticas básicas de DevOps utilizando herramientas open source.
- Mantener un repositorio profesional en GitHub con documentación en Markdown.
- Implementar una estrategia de ramificación basada en **GitHub Flow**.
- Usar **GitHub Actions** para ejecutar una pipeline de CI con linter de Markdown.
- (Opcional) Desplegar contenido automáticamente a través de **GitHub Pages**.

---

## 🔁 Flujo de Trabajo DevOps Implementado

### 📌 GitHub Flow

1. Todo desarrollo se realiza en ramas `feature/nombre`.
2. Los cambios se integran mediante Pull Requests hacia `main`.
3. La rama `main` se mantiene siempre estable.
4. Toda fusión a `main` requiere revisión y ejecución automática del pipeline de CI.

### ⚙️ CI con GitHub Actions

- Se ha implementado una pipeline que se ejecuta automáticamente en cada Pull Request hacia `main`.
- La acción realiza un análisis de calidad básica con `markdownlint`, asegurando consistencia en los archivos `.md`.

### 🌐 (Opcional) GitHub Pages

- El contenido del repositorio se despliega automáticamente como sitio web simple usando GitHub Pages desde la rama `main`, carpeta `/docs`.

---

## Estructura del Repositorio
