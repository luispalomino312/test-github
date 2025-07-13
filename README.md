# Proyecto DevOps & Project Management Fundamentals

Este repositorio forma parte del trabajo final del curso **DevOps & Project
Management Fundamentals**. Aquí se implementa un flujo DevOps básico utilizando
GitHub Flow y GitHub Actions, integrando prácticas de CI/CD.

---

## Estructura del repositorio

- README.md: Presentación del proyecto.
- workflow.md`: Explicación del flujo DevOps implementado.
- .github/workflows/ci.yml`: Pipeline de integración continua (CI).
- Otros archivos .md de documentación técnica.

---

## Flujo DevOps implementado

Se utilizó una estrategia GitHub Flow, donde :

- La rama main se mantiene siempre estable.
- Cada cambio se realiza en ramas de características (feature/ o fix/).
- Se crean Pull Requests (PR) hacia `main`.
- El pipeline CI se activa automáticamente en cada PR.
- Se ejecuta markdownlint para verificar calidad en archivos .md
