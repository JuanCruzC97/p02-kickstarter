# Info Dataset

## Descripción

El dataset utilizado en este proyecto fue armado previamente como parte del proyecto final de la materia Estadística Aplicada III - FIUBA. Los datos fueron preparados y se ha realizado feature engineering usando las variables originales. Fueron mejorados los valores vinculados a los tiers del proyecto realizando webscrapping.

El set de datos tiene **7.398** observaciones y **48** variables. 

El proyecto inicial usaba un modelo logístico para la predicción de éxito de las campañas de Kickstarter. 

## Variables del Dataset

### Variables Explicativas

* **fecha_inicial** : fecha de inicio de la campaña.
* **fecha_final** : fecha final de la campaña.
* **año_inicial** 
* **mes_inicial** 
* **dia_inicial** 
* **año_final** 
* **mes_final** 
* **día_final** 
* **pais** : País de origen de la campaña.
* **ciudad** : Ciudad de origen de la campaña.
* **categoria** : Categoría específica del producto.
* **categoria_principal** : Categoría general del producto.
* **proyecto_featured** : Proyecto promocionado.
* **descripcion_largo** : Largo de la descripción del proyecto.
* **descripcion_full_largo** : Largo de la descripción completa del proyecto.
* **titulo_largo** : Largo del título del proyecto.
* **cant_creaciones_dueño** : Cantidad de campañas del creador del proyecto.
* **cant_faqs** : Cantidad de preguntas frecuentes respondidas.
* **cant_imagenes** : Cantidad de imágenes de la publicación.
* **cant_videos** : Cantidad de videos de la publicación.
* **cant_tiers** : Cantidad de tiers definidos (aportes con retribución para el aportante)
* **tier_promedio**
* **tier_max**
* **tier_min**
* **duracion** : Duración total de la campaña.
* **moneda** : Moneda de publicación de la campaña.
* **objetivo_monto** : Monto objetivo a recaudar.
* **objetivo_ratio** : Cociente entre monto objetivo y duración del proyecto.
* **title** : Título del proyecto.
* **cotizacion** : Cotización de la moneda el día de la creación de la campaña.
* **moneda_igual_pais** : Si la moneda de publicación corresponde al país de origen o no.
* **dia_semana_inicial**
* **dia_semana_final**
* **weekend_inicial**
* **weekend_final**
* **primera_quincena_inicial**
* **primera_quincena_final**
* **id** : Identificación propia del proyecto.

### Variable Respuesta

* **exito** : Resultado de la campaña.
* **monto_obtenido** : Monto total recaudado.
* **monto_obtenido_porcentaje** : Porcentaje del monto objetivo recaudado.
* **estado**  : Estado final del proyecto.

### Variables Futuras

* cant_actualizaciones
* cant_backers
* cant_backers_tiers
* cant_comentarios
* backers_promedio_por_tier
* aporte_promedio_por_backer

