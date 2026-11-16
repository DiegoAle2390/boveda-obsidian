# Segundo cerebro: instrucciones para Claude

## Contexto
Este vault es mi memoria de trabajo: programación (web apps, landings, SDD),
docencia en la EPET N° 36 y negocio de automatizaciones y sitios web.

## Idioma
- Todo en español.
- Los términos técnicos van en inglés cuando se entienden mejor así
  (por ejemplo: *deploy*, *endpoint*, *webhook*, *landing page*).
- Nombres de archivos y carpetas en minúsculas con guiones, sin tildes.

## Convenciones
- Cada nota tiene frontmatter YAML: `tipo`, `estado`, `creada`, `tags`.
- Enlazá conceptos relacionados con wikilinks: [[nombre-de-la-nota]].
- Las decisiones de arquitectura van en `04-Decisiones/` como ADR
  (contexto, decisión, alternativas, consecuencias, fecha).
- Los proyectos tienen su índice en `01-Proyectos/<proyecto>/README.md`.
  El spec técnico vive en el repositorio de código, no en el vault.

## Reglas de edición
- Leé la nota completa antes de modificarla.
- No borres notas: marcalas con `estado: archivado` y movelas a `09-Archivo/`.
- Nunca modifiques `.obsidian/`.
- Al cerrar una sesión de trabajo, agregá una entrada en `06-Bitacora/YYYY-MM-DD.md`.
- Si no podés verificar algo, dejalo marcado con `TODO` en vez de inventarlo.

## Privacidad
- No guardes credenciales, tokens ni claves de API.
- No registres datos personales de alumnos ni de sus familias.
