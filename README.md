# Laboratorio: El Estándar de Colaboración 🧮

## 1. Contexto del Problema: La Calculadora de Equipo

[cite_start]Este proyecto consiste en el desarrollo de un script de Python llamado `math_operations.py`[cite: 3, 4]. [cite_start]El objetivo principal no es la complejidad técnica, sino la ejecución impecable de un flujo de trabajo profesional que garantice estabilidad, paralelismo, trazabilidad y calidad[cite: 5].

## 2. Briefing de Investigación

[cite_start]Antes de iniciar el desarrollo, el equipo definió los siguientes pilares de trabajo[cite: 7]:

- [cite_start]**Convención de Commits:** Uso de Conventional Commits (`feat:`, `fix:`, `docs:`)[cite: 9].
- [cite_start]**Gobernanza:** La rama `main` está protegida; queda prohibido el push directo para asegurar la revisión por pares[cite: 10, 15].
- [cite_start]**Estructura Semántica:** Las ramas se nombran según la tarea asignada (ej. `feat/addition`, `docs/readme`)[cite: 11, 18].

## 3. Stack Tecnológico

- [cite_start]**Lenguaje:** Python[cite: 2].
- [cite_start]**Control de Versiones:** Git CLI y GitHub[cite: 2].
- [cite_start]**Editor de Código:** VS Code[cite: 2].

## 4. Fase I: Configuración y Gobernanza

1. [cite_start]**Repositorio:** Creado por Coder A con un archivo `main.py` inicial[cite: 13].
2. [cite_start]**Protección de Rama:** Configuración de reglas que exigen al menos una aprobación de Pull Request (PR) antes de integrar cambios a `main`[cite: 15].
3. [cite_start]**Clonación:** Todos los integrantes trabajan sobre una copia local sincronizada[cite: 16].

## 5. Fase II: Desarrollo en Paralelo (Uso)

[cite_start]Cada integrante desarrolla su funcionalidad en una rama independiente para evitar interferencias[cite: 18]:

- [cite_start]**Coder A (feat/addition):** Implementó la función de suma[cite: 19].
- [cite_start]**Coder B (feat/subtraction):** Implementó la función de resta y generó un conflicto intencionado en la cabecera[cite: 19, 20].
- [cite_start]**Coder C (docs/readme):** Creó este archivo de documentación y estándares.

### Ejemplo de uso del script:

```python
from math_operations import add, resta

# Operación de Suma
print(add(10, 5))

# Operación de Resta
print(resta(10, 5))
```
