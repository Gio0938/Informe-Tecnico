# 📘 Informe Técnico de Estimación de Software

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge\&logo=latex\&logoColor=white)
![Ingeniería de Software](https://img.shields.io/badge/Ingeniería%20de%20Software-20232A?style=for-the-badge)
![UPPue](https://img.shields.io/badge/UPPue-Académico-blue?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-success?style=for-the-badge)

> 📚 Repositorio académico desarrollado para la asignatura de **Estandares y Metricas para el Desarrollo de Software** de la **Universidad Politécnica de Puebla (UPPue)** utilizando **LaTeX** para la elaboración de un informe técnico sobre métodos de estimación de software.

---

## 🎯 Objetivo

Este proyecto tiene como finalidad analizar y comparar diferentes técnicas de estimación utilizadas en Ingeniería de Software para determinar el tamaño, esfuerzo y complejidad de un sistema.

Las metodologías estudiadas incluyen:

* 📏 Puntos de Función (Function Points)
* 📝 Puntos de historias de usuario (Story Points)
* 👤 Casos de Uso (Use Case Points)
* 📊 Comparación de técnicas de estimación
* 💡 Análisis de resultados y conclusiones

---

## 📂 Estructura del Proyecto

```text
Informe_Estimacion_Software/
│
├── main.tex
├── referencias.bib
│
├── config/
│   ├── paquetes.tex
│   └── configuracion.tex
│
├── portada/
│   └── portada.tex
│
├── capitulos/
│   ├── 01_introduccion.tex
│   ├── 02_descripcion_software.tex
│   ├── 03_puntos_funcion.tex
│   ├── 04_story_points.tex
│   ├── 05_casos_uso.tex
│   ├── 06_comparacion.tex
│   └── 07_conclusiones.tex
│
├── anexos/
│   ├── anexo_a.tex
│   └── anexo_b.tex
│
├── imagenes/
│   ├── logo_uppuebla.png
│   ├── diagrama_casos_uso.png
│   └── arquitectura.png
│
└── tablas/
    ├── tabla_fp.tex
    ├── tabla_sp.tex
    └── tabla_ucp.tex
```

---

## 📚 Contenido del Informe

### 🔹 Capítulo 1 — Introducción

Presentación del problema, contexto, objetivos y justificación del proyecto.

### 🔹 Capítulo 2 — Descripción del Software

Descripción general del sistema analizado, alcance y funcionalidades principales.

### 🔹 Capítulo 3 — Puntos de Función

Aplicación de la metodología **Function Point Analysis (FPA)** para estimar el tamaño funcional del software.

### 🔹 Capítulo 4 — Story Points

Estimación basada en metodologías ágiles utilizando Story Points.

### 🔹 Capítulo 5 — Casos de Uso

Aplicación del método **Use Case Points (UCP)** para determinar el esfuerzo de desarrollo.

### 🔹 Capítulo 6 — Comparación de Métodos

Análisis comparativo entre las distintas técnicas de estimación.

### 🔹 Capítulo 7 — Conclusiones

Resultados obtenidos, ventajas, limitaciones y conclusiones finales.

---

## 🛠️ Tecnologías Utilizadas

| Herramienta                 | Uso                     |
| --------------------------- | ----------------------- |
| 📄 LaTeX                    | Redacción del informe   |
| 📚 BibTeX                   | Gestión bibliográfica   |
| 💻 Papeeria                 | Edición colaborativa    |
| ⚙️ TeX Live / MiKTeX        | Compilación local       |
| 📝 TexWorks + LaTeX Workshop| Desarrollo del proyecto |

---

## 🚀 Compilación

Para generar el PDF del informe:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

También puedes abrir el proyecto en **Overleaf** y compilarlo directamente.

---

## 📖 Bibliografía

Las referencias bibliográficas se administran mediante:

```text
referencias.bib
```

empleando **BibTeX** para mantener una gestión organizada de las fuentes académicas.

---

## 📸 Recursos Gráficos

El proyecto incluye:

* 🏛️ Logotipo institucional
* 🖼️ Diagramas de arquitectura
* 📊 Tablas de estimación
* 📈 Figuras de apoyo para el análisis

---

## 🎓 Información Académica

**Universidad Politécnica de Puebla (UPPue)**

📍 Carrera: Ingeniería en Tecnologías de la Información e Innovación Digital

📚 Asignatura: Estandares y Metricas para el Desarrollo de Software

👨‍🎓 Autor: **Giovani**

📅 Año: 2026

---

## ⭐ Contribuciones

Si encuentras errores o deseas mejorar la plantilla, puedes:

* 🍴 Hacer un Fork
* 🌟 Dar una estrella al repositorio
* 📝 Crear un Pull Request
* 🐞 Reportar errores mediante Issues

---

## 📜 Licencia

Este proyecto se distribuye con fines **académicos y educativos**.

> ✨ "La estimación de software no consiste en predecir el futuro con exactitud, sino en reducir la incertidumbre para tomar mejores decisiones."
