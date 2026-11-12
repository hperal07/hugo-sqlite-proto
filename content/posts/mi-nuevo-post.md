---
title: "Consultas SQL en un sitio estático"
date: 2026-11-12
tags: [sql, hugo]
draft: false
---
SQLite trabaja solo durante el build: lee los Markdown, guarda los datos
en una tabla y las consultas SQL generan el JSON que usa la web.
En producción no queda ninguna base de datos, solo ficheros estáticos.
