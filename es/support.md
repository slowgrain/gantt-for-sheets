---
layout: default
title: Ayuda
lang: es-419
home_path: /es/
support_path: /es/support/
privacy_path: /es/privacy/
terms_path: /es/terms/
permalink: /es/support/
---

# Asistencia — Gantt Chart for Sheets

**Correo: slowgrain.dev@gmail.com** — respondemos en un plazo de cinco días laborables.

## Primeros pasos

1. Abre la hoja de cálculo que contiene tu lista de tareas.
2. Selecciona **Extensiones → Gantt Chart for Sheets → Crear diagrama de Gantt**.
3. Aparecerá una pestaña **Gantt** con el gráfico. La lista original no se modifica.

Vuelve a ejecutar el complemento cuando cambie el plan; el gráfico se reconstruye desde cero.

## Vincular una hoja existente

La tabla puede empezar en cualquier celda y las columnas pueden estar en cualquier orden. Se reconocen encabezados en inglés, coreano, japonés, español, portugués, francés y alemán.

Si no se detectan correctamente, selecciona **Herramientas de Gantt → Vincular y previsualizar hoja de tareas**. Elige la fila de encabezados y asigna las columnas. Antes de guardar verás hasta seis tareas reales, las fechas calculadas y el número de tareas sin inicio o sin programar. La configuración se guarda por pestaña. **No usar** impide que se infiera ese campo.

| Campo | Ejemplos de encabezados | Obligatorio |
|---|---|---|
| Nombre de tarea | Task, Tarea, Arbeit, 作業 | Sí |
| Inicio | Start, Inicio, Début, 開始 | Sí* |
| Fin o duración | End, Fin, Durée, 日数 | Uno de los dos |
| Predecesoras | After, Predecessors, Después de | No |
| Progreso | Progress, Progreso, Avancement | No |
| Responsable | Owner, Responsable, 担当者 | No |
| WBS / tarea superior | Level, Parent, Nivel | No |
| Esfuerzo y capacidad diaria | Total effort, Hours per day | No |

* Una tarea puede omitir el inicio si una predecesora permite calcularlo o si es una fase con tareas secundarias.

## Fechas

Usa fechas ISO (2026-04-03) o celdas de fecha de la hoja para evitar ambigüedades. El complemento infiere el orden día/mes a partir de valores claros; si no hay evidencia, aplica el orden habitual del idioma.

## Predecesoras

Introduce el ID de la tarea anterior en la columna Predecesoras. `12` empieza después de terminar la tarea 12; `12+3` añade tres días; `12-1` indica un día de adelanto. Separa varias tareas con comas.

## Carga y horas

Asigna personas a las tareas para ver solapamientos y capacidad diaria. **Esfuerzo total (horas)** se divide por igual entre las personas asignadas y los días laborables previstos. **Horas por día** tiene prioridad cuando se introduce directamente para cada persona. Las tareas sin horas se excluyen del cálculo, sin inventar una estimación.

## Preguntas frecuentes

**Falta una tarea en el gráfico.** Debajo del gráfico aparece el motivo. Revisa el inicio, el fin, la duración y las dependencias circulares.

**Quiero excluir fines de semana.** Activa **Excluir fines de semana** en el menú. Los días festivos se configuran por pestaña.

**El gráfico es demasiado ancho.** La escala cambia automáticamente entre días, semanas, meses y trimestres. No hay una duración máxima.

**Tengo más de 50 tareas.** El plan gratuito permite 50; Pro elimina el límite. Las tareas que superan el límite se informan, no desaparecen en silencio.

## Licencia

Compra Pro en https://slowgrain.app/gantt-for-sheets/#pro

Para introducirla, ve a **Extensiones → Gantt Chart for Sheets → Licencia → Introducir clave de licencia**. La clave se guarda en tu cuenta de Google y se introduce una sola vez.

Si no recibes la clave, la pierdes o no se acepta, escribe al correo de asistencia con la referencia del pedido. Las claves empiezan por `GS1.` y no contienen espacios.

## Informar de un problema

Escribe a **slowgrain.dev@gmail.com** e incluye:

- qué esperabas y qué ocurrió
- una captura del gráfico o del error
- si es posible, una copia de la hoja sin información confidencial

El complemento no puede enviarnos datos por sí solo; adjunta los archivos que quieras compartir.
