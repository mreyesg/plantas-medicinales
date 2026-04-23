# Contributing to plantas-medicinales

Gracias por tu interés en contribuir. Este documento describe el flujo básico y las reglas para contribuir con parches, correcciones, documentación o ideas.

## Resumen rápido
- Si encuentras un bug, abre un *issue* con pasos para reproducirlo.
- Para proponer cambios, crea una rama nueva y envía un *pull request* (PR).
- Sigue el checklist en **PR checklist** antes de solicitar revisión.

## Reportar un problema (issue)
1. Comprueba si ya existe un *issue* relacionado.
2. Crea un nuevo *issue* con un título claro y una descripción que incluya:
   - Pasos para reproducir.
   - Resultado esperado vs resultado actual.
   - Versión del proyecto / entorno si aplica.

## Proponer cambios (pull request)
1. Haz *fork* del repositorio (si no tienes permisos directos) y clona tu fork.
2. Crea una rama descriptiva: `feature/<breve-descripción>` o `fix/<breve-descripción>`.
3. Haz commits pequeños y atómicos con mensajes claros (ver Convención de commits abajo).
4. Empuja la rama a tu fork y abre un PR hacia `main` del repositorio original.

## Convención de commits
Preferimos mensajes claros. Ejemplo breve recomendado (Conventional Commits-like):

- `feat: añadir importación de datos desde CSV`
- `fix: corregir validación de fecha`
- `docs: actualizar README`

## Estilo de código y formateo
- Sigue las reglas del linter/configuración del proyecto (si existe).
- Ejecuta el formateador antes de crear PR (por ejemplo `prettier` o `black` según corresponda).

## Tests y CI
- Incluye tests para cambios funcionales cuando sea posible.
- Asegúrate de que la suite de CI pase antes de pedir revisión.

## PR checklist
- [ ] El código tiene descripciones de lo que hace el cambio.
- [ ] Se añadieron/actualizaron tests cuando aplica.
- [ ] El formateo y linter están limpios.
- [ ] No se incluyen archivos sensibles ni credenciales.

## Entorno local (rápida guía)
1. Clonar el repo: `git clone git@github.com:mreyesg/plantas-medicinales.git`
2. Crear y activar entorno si corresponde (p. ej. `python -m venv .venv`).
3. Instalar dependencias y ejecutar tests.

## Código de conducta
Por favor sigue normas básicas de respeto y colaboración. Si quieres, podemos añadir un `CODE_OF_CONDUCT.md` separado.

## Contacto
Si tienes preguntas sobre el proceso, abre un *issue* y etiqueta a los mantenedores.
