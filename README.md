# Análisis de la Fuerza Gravitacional con LaTeX

Este repositorio contiene un proyecto desarrollado en Visual Studio Code utilizando LaTeX. El objetivo del proyecto es analizar la fuerza gravitacional mediante la comparación de datos experimentales y teóricos, aplicando la Ley de Gravitación Universal de Newton y evaluando el error porcentual entre ambos conjuntos de datos.

## Descripción del Proyecto

En este trabajo se incluye:
- Un análisis de la fuerza gravitacional utilizando la fórmula:
  $$
  F_{\text{teo}}(m_1, m_2, r) = G\,\frac{m_1\,m_2}{r^2}, \quad \text{donde} \quad G = 6.67 \times 10^{-11}\,\text{N}\,\text{m}^2/\text{kg}^2.
  $$
- El cálculo del error porcentual entre la fuerza observada y la teórica, definido como:
  $$
  \text{Error}(\%) = \left|\frac{F_{\text{obs}} - F_{\text{teo}}}{F_{\text{teo}}}\right| \times 100\%.
  $$
- Una tabla que compara los valores observados y teóricos, y una conclusión basada en el análisis realizado.

## Requisitos

- [LaTeX](https://www.latex-project.org/) para la compilación de los documentos.
- [Visual Studio Code](https://code.visualstudio.com/) como entorno de desarrollo.
- Extensiones recomendadas para trabajar con LaTeX en VSCode, como **LaTeX Workshop**.

## Cómo Empezar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jcamilofarfan/ACA_Fisica_Mecanica_y_Laboratorio.git
   ```
   	2.	Abre el proyecto en Visual Studio Code.
	3.	Asegúrate de tener instaladas las herramientas necesarias para compilar documentos LaTeX.
	4.	Compila el documento principal para generar el PDF del reporte.

Documentación Adicional

Para una guía detallada sobre cómo escribir documentos LaTeX en Visual Studio Code utilizando un Mac, consulta el siguiente manual:

[How to Write LaTeX Documents with Visual Studio Code on Mac](https://sudorealm.com/blog/how-to-write-latex-documents-with-visual-studio-code-on-mac)

Licencia

Este proyecto se distribuye bajo la Licencia MIT.