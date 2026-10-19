# Proyecto de prácticas de Odoo 19

## Objetivo

Gestionar PYMES de albañilería con un software completo, sencillo, seguro y fiable.

## Índice

- [Requisitos](#requisitos)
- [Estructura](#estructura)
- [Entorno de trabajo](#entorno-de-trabajo)
- [Arranque](#arranque)
- [Comprobaciones](#comprobaciones)
- [Incidencias](#incidencias)

## Requisitos

| Elemento | Versión utilizada o procedencia |
| --- | --- |
| Odoo | 19.0, revisión f35003a1 (2026-10-19) |
| Python | 3.14.4 |
| PostgreSQL | psql 18.6 |
| Sistema | Ubuntu 26.04.1 LTS en WSL 2|

## Estructura

- `custom_addons/`: módulos desarrollados en clase.
- `docs/img/`: capturas de documentación sin datos privados.
- `requirements.txt`: dependencias de Python de referencia.
- `GUIA_PROYECTO.md`: instrucciones de este proyecto.

El código base de Odoo y `.venv/` no se incluyen en Git.
El README original de Odoo se conserva en la instalación.
El repositorio no contiene la base de datos ni el filestore.

Módulos desarrollados: todavía no he desarrollado ninguno.

## Entorno de trabajo

- Editor: Visual Studio Code conectado a WSL.
- Control de versiones: Git, con autoría configurada en este repositorio.
- Entorno virtual de Python: `.venv/` (local, no versionado).

PENDIENTE: indica cómo se activa el entorno virtual en tu instalación.

## Arranque

PENDIENTE: escribe aquí el comando real con el que arrancas Odoo,
indicando desde qué carpeta se ejecuta.

## Comprobaciones

- [X] La terminal es de WSL y está en la raíz del proyecto.
- [X] `git status` indica que no hay cambios pendientes.
- [X] `git log --oneline` muestra los commits esperados.
- [X] Odoo arranca y se puede acceder desde el navegador.

## Incidencias

Ninguna