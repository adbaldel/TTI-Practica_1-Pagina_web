---
title: "Mi Experiencia con GitHub Pages"
date: 2025-02-10T10:00:00+01:00
author: "Adrian"
draft: false
tags: ["git", "practica", "desarrollo"]
slug: "mi-experiencia-github"
---

# Bienvenido a mi Portafolios

Esta es mi primera entrada creada para la **Práctica I** de la asignatura. Aquí explicaré lo que he aprendido sobre generadores de sitios estáticos.

## ¿Qué herramienta estoy usando?

Según la terminación de mi DNI, estoy utilizando esta tecnología: **Hugo** (Go)

## ¿Qué he aprendido?

Durante la práctica, he aprendido a crear una página web con **Hugo**:

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```
a subirla a Github:
```
git remote add origin https://github.com/adbalde1/TTI-Practica_1-Pagina_web.git
git branch -M main
git push -u origin main
```
y desplegarla en Github Pages mediante una Github Action que hay en el marketplace para Go.
