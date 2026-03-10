# Análisis de Hacker News con MongoDB

## Introducción

Este proyecto implementa un pipeline completo de análisis de datos utilizando:

- API pública de Hacker News

- MongoDB como base de datos NoSQL

- Python para extracción y procesamiento

- Pandas para análisis

- Matplotlib para gráficos 

- Generación automática de reportes en Excel

## Almacenamiento en MongoDB

Los datos se obtienen desde la API pública de Hacker News.

![datos](https://github.com/user-attachments/assets/a7ebf509-c425-4c91-a07d-56c7a533f018)

## Análisis de datos

Los datos almacenados en MongoDB se cargan en un DataFrame de Pandas para realizar análisis.

### Principales análisis realizados:

#### Top usuarios con mayor score

Se calcula el score total acumulado por usuario para identificar los usuarios más influyentes.

![top_usuarios](https://github.com/user-attachments/assets/d101e0c6-3a99-4622-a4ed-1c5faca7795e)

#### Posts más populares

Se identifican los posts con mayor score.

![post mas populares](https://github.com/user-attachments/assets/9e54eb61-3007-41e4-85b8-6cae38324c0b)

Esto permite detectar contenido con mayor impacto dentro de la comunidad.

#### Actividad por hora

Se analiza la distribución de publicaciones por hora del día para identificar patrones de actividad.

![post_hora](https://github.com/user-attachments/assets/0116c88b-938f-4d24-a59a-4e1db56740a5)

#### Relación entre longitud del título y popularidad

![longitud](https://github.com/user-attachments/assets/910126bd-3269-44e5-b372-4411e9260396)

## Generación automática de reportes

El proyecto genera automáticamente un archivo: reporte_hackernews.xlsx

El reporte contiene múltiples hojas:

- dataset

Contiene todos los datos descargados.

- top_users

Usuarios con mayor score acumulado.

- top_posts

Posts con mayor score.

- activity_hour

También se genera una gráfica automática en Excel que muestra la actividad por hora.

Esto simula un flujo común en empresas donde se generan reportes periódicos para análisis de negocio

## 17. Conclusiones

- El usuario todsacerdoti presenta el mayor score total entre los posts analizados.

- Existe una diferencia significativa entre el primer usuario y el resto del ranking.

- El mayor volumen de posts ocurre entre 14:00 y 21:00 horas.

- Los temas más populares incluyen tecnología, economía y política.

- No se observa una relación clara entre longitud del título y popularidad.





