# Análisis de Factores que Influyen en la Blastulación en Tratamientos de Fertilidad

Este proyecto se centra en el análisis estadístico de tratamientos de fertilidad, específicamente investigando los factores que afectan la blastulación durante las primeras y segundas estimulaciones ováricas. A través de un enfoque en dos grupos de tratamiento - antagonistas de la GnRH y gestágenos - buscamos identificar variables predictoras clave y optimizar los resultados de los tratamientos de fertilidad.

## Objetivo

El objetivo principal de este estudio es comprender realizar un análisis estadístico univariante, bivariante (análisis de asociación) y multivariante con la finalidad de comprender mejor cómo las variables comunes entre pacientes sometidos a tratamientos de fertilidad influencian la blastulación, un indicador del éxito reproductivo. 

## Metodología

Se han empleado modelos de regresión logística y análisis de asociación para explorar la relación entre diversas variables y los eventos de blastulación. El estudio adopta las siguientes fases:

1. Limpieza de datos: Trtamiento de ficheros, recodificación de variables categóricas e imputación de datos perdidos.
2. Análisis estadístico univariante: Tanto numérico como estadístico, se centra en comprender la distribución de nuestros datos y poder cuantificar conclusiones (simetría, sesgo, desbalance de clases, etc.)
3. Análisis de asociación: Esta fase se centra en la aplicación de tests estadísticos que cumplan con las condiciones establecidas por la naturaleza de los pares de variables a analizar.
4. Análisis multivariante: Finalmente, se aplica un modelo explicativo de regresión logística entre variables comunes y de primera estimulación con la blastulación de primera y segunda estimulación, respectivamente, para intentar inferir el evento de blastulación a partir del menor número de variables. 

## Consecuencias del Estudio

Los resultados de este estudio tienen implicaciones significativas:

- **Económicas**: Optimizar los tratamientos de fertilidad puede reducir los costos asociados para las clínicas y las familias.
- **Salud Mental**: Reducir la carga emocional para las parejas, mejorando su bienestar durante los procesos de fertilidad.
- **Clínicas de Fertilidad**: Mejorar las tasas de éxito de los tratamientos, reforzando la reputación y la calidad del servicio ofrecido.

## Visualización del desarrollo del estudio

El estudio ha sido implementado en R, utilizando el paquete `Rshiny` se ha podido lanzar una aplicación a la web en la cual se pueden consultar los resultados del estudio. Esta web puede consultarse [aquí](https://mario-pascual-rshiny-uma.shinyapps.io/entrega-fertilidad-mindat/). 

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - vea el archivo `LICENSE` para más detalles.

## Contacto

Para poder contactar conmigo, por favor redirigirse a mi perfil de [LinkedIn](https://www.linkedin.com/in/mario-pascual-gonzalez/).


<p align="center">
  <img src="https://github.com/MarioPasc/Mineria-de-Datos-con-R/assets/120520768/8116be8d-7c0d-4564-9678-d1fda0064a6a" width="100" title="Universidad de Málaga">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://www.r-project.org/logo/Rlogo.png" width="100" title="Logo de R">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://www.rstudio.com/wp-content/uploads/2018/10/RStudio-Logo-Flat.png" width="220" title="Logo de RStudio">
</p>
