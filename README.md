# Laboratorio: El Estándar de Colaboración

## 1. Contexto del Problema: La Calculadora de Equipo

Este proyecto consiste en el desarrollo de un script de Python llamado `math_operations.py`. El objetivo principal no es la complejidad técnica, sino la ejecución impecable de un flujo de trabajo profesional que garantice estabilidad, paralelismo, trazabilidad y calidad.

## 2. Briefing de Investigación

Antes de iniciar el desarrollo, el equipo definió los siguientes pilares de trabajo:

- **Convención de Commits**: Uso de Conventional Commits (`feat:`, `fix:`, `docs:`).
- **Gobernanza**: La rama `main` está protegida; queda prohibido el push directo para asegurar la revisión por pares.
- **Estructura Semántica**: Las ramas se nombran según la tarea asignada (ej. `feat/addition`, `docs/readme`).

## 3. Stack Tecnológico

Para este laboratorio se utiliza el siguiente stack:

- **Lenguaje**: Python 3.x
- **Herramientas**: Git CLI y GitHub.
- **Editor**: VS Code.

## 4. Fase I: Configuración y Gobernanza

1. **Repositorio**: Creado por Coder A con un archivo `main.py` inicial.
2. **Protección de Rama**: Configuración de reglas que exigen al menos una aprobación de Pull Request (PR) antes de integrar cambios a `main`.
3. **Clonación**: Todos los integrantes trabajan sobre una copia local sincronizada.

## 5. Fase II: Desarrollo en Paralelo (Uso)

Cada integrante desarrolla su funcionalidad en una rama independiente para evitar interferencias:

- **Coder A (feat/addition)**: Implementó la función de suma.
- **Coder B (feat/subtraction)**: Implementó la función de resta y generó un conflicto intencionado en la cabecera.
- **Coder C (docs/readme)**: Creó este archivo de documentación y estándares.

### Ejemplo de uso del script:

```python
from math_operations import add, resta

# Operación de Suma
print(add(10, 5))

# Operación de Resta
print(resta(10, 5))
```
