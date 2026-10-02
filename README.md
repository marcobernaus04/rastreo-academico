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

Abrila en https://marcobernaus04.github.io/rastreo-academico/ o descargá `index.html` y abrilo en el navegador. No necesita instalación.

- **Sin iniciar sesión**, el progreso se guarda en el navegador (`localStorage`).
- **Con sesión iniciada** (con Google o con un enlace por mail, sin contraseña), el progreso se guarda en la nube con Supabase y se ve igual desde cualquier dispositivo. La primera vez que entrás con una cuenta, se sube lo que ya tenías en ese navegador.

### Inicio de sesión

Desde el botón **Iniciar sesión** hay dos formas de entrar:

- **Entrar con Google:** elegís tu cuenta de Google y volvés a la app con la sesión abierta. La app solo usa tu mail para identificar la cuenta.
- **Enlace por mail:** escribís tu mail y te llega un enlace para entrar; hay que abrirlo en el mismo navegador.

Si usás el mismo mail en las dos formas, es la misma cuenta y ves el mismo progreso.

La clave de Supabase que aparece en el código es la pública (publishable). Cada persona solo puede leer y modificar su propia fila, por las reglas de seguridad de la tabla.

## Notas

- Para cursar se piden las correlativas regulares o aprobadas que indica la ordenanza. Para rendir un final, la app pide todas las correlativas aprobadas.
- La lista de electivas no viene precargada: cada regional define las suyas.
- El dictado anual o cuatrimestral lo define cada regional y se carga a mano.
- [Política de privacidad](https://marcobernaus04.github.io/rastreo-academico/privacidad.html) y [condiciones del servicio](https://marcobernaus04.github.io/rastreo-academico/condiciones.html).
