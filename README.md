# Mi Plan ISI

Seguimiento del plan de estudio de **Ingeniería en Sistemas de Información (UTN, Plan 2023)**, pensado para la Facultad Regional Rosario.

## Qué hace

- Las 36 materias obligatorias organizadas por año, con horas y correlativas según las Ordenanzas CSU 1877/2022 y 1878/2022.
- Estado por materia (pendiente, cursando, regular, aprobada), nota y dictado (anual o cuatrimestral).
- Calcula qué materias podés cursar y qué finales podés rendir.
- Electivas con contador de horas aprobadas y faltantes sobre las 20 hs que pide el plan.
- Porcentaje de carrera aprobada (100 % = recibido), promedio y finales pendientes.
- Copias del progreso con nombre, y exportar o importar como archivo `.json`.

## Cómo usarla

Es un solo archivo: abrí `index.html` en el navegador. No necesita instalación ni servidor.

Abierta así, el progreso se guarda en el navegador (`localStorage`). La misma página publicada como Artifact en claude.ai guarda el progreso en la cuenta de cada persona.

## Notas

- Para cursar se piden las correlativas regulares o aprobadas que indica la ordenanza. Para rendir un final, la app pide todas las correlativas aprobadas.
- La lista de electivas no viene precargada: cada regional define las suyas.
- El dictado anual o cuatrimestral lo define cada regional y se carga a mano.
