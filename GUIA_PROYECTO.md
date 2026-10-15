# Proyecto de prácticas de Odoo 19

## Objetivo

PENDIENTE: explica qué proceso empresarial resolverá el proyecto
y qué podrá hacer la persona que lo utilice.

La guía documenta el entorno de prácticas.

> Nota: los datos de la base de datos se copian por separado.

## Índice

- [Requisitos](#requisitos)
- [Estructura](#estructura)
- [Módulos](#módulos)
- [Comprobaciones](#comprobaciones)

## Requisitos

| Elemento | Versión utilizada o procedencia |
| --- | --- |
| Odoo | 19.0.post20261008 |
| Python | 3.12.3 |
| PostgreSQL | 16.15 |
| Sistema | Ubuntu 24.04.5 LTS en WSL |

## Estructura

- `custom_addons/`: módulos desarrollados en clase.
- `docs/img/`: capturas de documentación sin datos privados.
- `requirements.txt`: dependencias de Python de referencia.
- `GUIA_PROYECTO.md`: instrucciones de este proyecto.

El código base de Odoo y `.venv/` no se incluyen en Git.
El README original de Odoo se conserva en la instalación.
El repositorio no contiene la base de datos ni el filestore.

## Módulos

Todavía no he desarrollado ningún módulo. Cuando exista, se indicará
su nombre técnico, finalidad, dependencias y estado.

## Comprobaciones

Antes de cada commit, desde la raíz del proyecto:

```bash
git status
git diff --staged
```

- [x] Comprobar la rama activa.
- [x] Revisar el contenido preparado.
- [ ] Crear el commit de documentación.