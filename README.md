# Laboratorio: El Estándar de Colaboración 🧮

Este proyecto consiste en el desarrollo de un módulo de Python llamado `math_operations.py`. El objetivo principal no es la complejidad técnica, sino la ejecución impecable de un flujo de trabajo profesional que garantice estabilidad, paralelismo, trazabilidad y calidad en el desarrollo de software.

## 1. Contexto del Problema: La Calculadora de Equipo

El equipo debe construir una herramienta de operaciones matemáticas básica trabajando de forma colaborativa. Para asegurar la integridad del código, se ha establecido una estructura donde la rama principal está protegida y todo cambio debe ser auditado antes de su integración.

## 2. Briefing de Investigación

Antes de iniciar el desarrollo, el equipo definió los siguientes pilares de trabajo:

- **Convención de Commits:** Uso de [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`) para un historial legible.
- **Gobernanza:** La rama `main` está protegida; queda prohibido el `push` directo para asegurar la revisión por pares.
- **Estructura Semántica:** Las ramas se nombran según la tarea: `feat/addition`, `feat/subtraction` y `docs/readme`.

## 3. Stack Tecnológico

- **Lenguaje:** Python 3.x
- **Control de Versiones:** Git CLI & GitHub
- **Editor de Código:** VS Code
- **Entorno de Desarrollo:** Virtualenv (`.venv`)

## 4. Fase I: Configuración y Gobernanza

1. **Repositorio:** Creado por Coder A con un archivo `main.py` inicial.
2. **Protección de Rama:** Configuración de reglas en GitHub que exigen al menos una aprobación de Pull Request (PR) para fusionar cambios en `main`.
3. **Clonación:** Todos los integrantes trabajan sobre una copia local sincronizada.

## 5. Fase II: Desarrollo en Paralelo (Uso)

Cada integrante desarrolla su funcionalidad en una rama independiente para evitar interferencias directas
