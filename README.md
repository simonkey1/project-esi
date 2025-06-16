**# Análisis de Ingresos por Género (ESI) – Proyecto de Data Analysis Junior**

**Descripción general**
Este proyecto analiza las brechas salariales de género en el mercado laboral chileno utilizando los datos de la Encuesta Suplementaria de Ingresos (ESI) 2017–2022. Como candidato a analista de datos junior, demuestro mi capacidad para manipular grandes volúmenes de datos, aplicar técnicas de limpieza, transformación y visualización, y presentar hallazgos clave de manera clara y accionable.

---

## 💼 Objetivos y alcance

* **Objetivo principal:** Identificar y cuantificar brechas de ingreso entre hombres y mujeres en distintos segmentos (sexo, edad, nivel educativo, sector económico, macrorregiones).
* **Público objetivo:** Equipos de recursos humanos, líderes de área y consultoras interesadas en igualdad salarial y políticas de diversidad.

---

## 🛠 Tecnologías y herramientas

* **Lenguaje:** R
* **Paquetes principales:** tidyverse (dplyr, ggplot2), haven, psych, kableExtra, broom, scales
* **Formato de entrega:** R Markdown con salida HTML (tema Flatly, TOC flotante)

---

## 🔍 Metodología

1. **Importación y limpieza de datos**

   * Lectura de archivos `.sav` de la ESI 2017–2022 con `read_sav()`.
   * Selección y recodificación de variables clave: sexo, ocupación, ingresos, edad, nivel educativo, región, sector.
   * Cálculo de variables derivadas: ingreso por hora, tramos de ingreso (en SM), grupos de edad.

2. **Análisis descriptivo**

   * Tablas de frecuencia y proporciones por sexo.
   * Estadísticos centrales (media, mediana, asimetría, curtosis) de ingresos y edad.
   * Visualizaciones: histogramas, gráficos de barras y pie charts estilizados.

3. **Análisis bivariado**

   * Comparación de ingresos medios por macrorregión, grupo de edad y categoría ocupacional mediante ANOVA y test post-hoc (TukeyHSD).
   * Cálculo de brechas percentuales de género y su representación gráfica.

4. **Evolución temporal (2017–2022)**

   * Tendencias anuales de ingresos medios, medianas y por hora.
   * Pruebas t para evaluar significancia de diferencias de género.

---

## 📈 Resultados clave

* **Brecha salarial general:** En promedio, las mujeres ganan entre un 15% y 20% menos que los hombres (según tramo y año).
* **Segmentos más afectados:** Mayores diferencias en grupos de edad 35–44 y en servicios domésticos.
* **Evolución temporal:** Ligera reducción de la brecha entre 2017 y 2022, pero persiste en todos los sectores.

---

## 🔧 Cómo reproducir este proyecto

1. Clonar repositorio:

   ```bash
   git clone https://github.com/simonkey1/project-esi.git
   cd project-esi
   ```
2. Instalar dependencias en R:

   ```r
   install.packages(c(
     "tidyverse", "haven", "psych", "kableExtra",
     "scales", "broom", "wesanderson", "prettydoc"
   ))
   ```
3. Ejecutar y knit el archivo R Markdown:

   * Abrir `analysis.Rmd` en RStudio.
   * Ejecutar "Knit" para generar `output/index.html`.

---

## 🎯 Habilidades demostradas

* Limpieza y transformación de datos con **dplyr** y **purrr**.
* Análisis estadístico descriptivo e inferencial (t-test, ANOVA, TukeyHSD).
* Creación de reportes reproducibles con **R Markdown**.
* Visualización efectiva con **ggplot2** y mejora de tablas con **kableExtra**.
* Documentación técnica clara y orientada a stakeholders.

---

## 📫 Contacto

**Simón Gómez**
GitHub: [simonkey1](https://github.com/simonkey1)
LinkedIn: [linkedin.com/in/cristobalgomez](https://www.linkedin.com/in/cristobalgomez)
Email: [cristobalc.gomez@mail.udp.cl](mailto:cristobalc.gomez@mail.udp.cl)

---

*Este README está diseñado para destacar competencias clave y resultados de negocio, facilitando la evaluación por parte de reclutadores y equipos de contratación en roles de Data Analyst junior.*
