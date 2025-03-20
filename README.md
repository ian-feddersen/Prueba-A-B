# 📊Prueba-A-B
Pruebas A/B para un Sistema de Recomendaciones

# 📌Descripción del Proyecto
Este proyecto evalúa los resultados de una prueba A/B realizada por una tienda en línea internacional. El objetivo es determinar si un sistema de recomendaciones mejorado incrementa la conversión de los usuarios en tres etapas clave del embudo de ventas:

Vistas de la página del producto (product_page).

Agregar productos al carrito (product_cart).

Compras (purchase).

## La prueba A/B se realizó con dos grupos:

### Grupo A (Control): Utiliza el sistema de recomendaciones actual.

### Grupo B (Prueba): Utiliza el nuevo sistema de recomendaciones mejorado.

El objetivo esperado era un incremento del 10% en la conversión en cada etapa del embudo.

## 🛠Tecnologías Utilizadas
Lenguajes de programación: Python

Librerías principales: Pandas, Matplotlib, Seaborn, Statsmodels

Herramientas: Jupyter Notebook

Métricas clave: Conversión, Prueba Z, Tasa de Retención

## 📊Estructura del Proyecto
### 1. Carga y Preprocesamiento de Datos
Carga de datos: Se cargaron los datasets ab_project_marketing_events_us.csv, final_ab_new_users_upd_us.csv, final_ab_events_upd_us.csv y final_ab_participants_upd_us.csv.

Limpieza y transformación: Se verificaron valores nulos y duplicados, y se convirtieron los tipos de datos.

### 2. Análisis Exploratorio de Datos (EDA)
Conversión en el Embudo: Se analizó la conversión en cada etapa del embudo para ambos grupos.

Distribución de Eventos: Se evaluó la distribución de eventos por usuario y por día.

### 3. Pruebas Estadísticas (Prueba Z)
Comparación de Grupos: Se aplicó la prueba Z para comparar las proporciones de conversión entre los grupos A y B.

Resultados: Se identificaron diferencias estadísticamente significativas en las etapas de product_page y purchase.

### 4. Conclusiones y Recomendaciones
Grupo A (Control): Mostró una mayor tasa de conversión en las etapas clave.

Grupo B (Prueba): Cumplió con el objetivo del 10%, pero no superó al Grupo A.

## 📈Recomendaciones: Optimización del sistema de recomendaciones, segmentación de usuarios y pruebas adicionales.

#### Resultados Clave
Conversión en el Embudo
#### Grupo A:

product_page: 66.14%

product_cart: 31.53%

purchase: 34.06%

#### Grupo B:

product_page: 64.24%

product_cart: 32.83%

purchase: 32.36%

Pruebas Estadísticas
product_cart: No hubo diferencias estadísticamente significativas (Valor P = 0.102).

product_page: Diferencia significativa (Valor P = 0.0185), con el Grupo A mostrando un mejor desempeño.

purchase: Diferencia significativa (Valor P = 0.0336), con el Grupo A logrando mejores resultados.

# 📈Conclusiones y Recomendaciones
### 1. Optimización del Sistema de Recomendaciones
Realizar un análisis más detallado de las variables del sistema de recomendaciones en el Grupo B.

Considerar mejoras en la personalización o en los algoritmos de recomendación.

### 2. Segmentación de Usuarios
Identificar subgrupos de usuarios que responden mejor al nuevo sistema de recomendaciones.

Implementar estrategias personalizadas para estos subgrupos.

### 3. Pruebas Adicionales
Realizar pruebas A/B adicionales con ajustes específicos en el sistema de recomendaciones.

Evaluar el impacto de diferentes tipos de recomendaciones.

### 4. Comunicación Proactiva
Enviar recordatorios y ofertas personalizadas a usuarios con baja frecuencia de interacción.

Utilizar campañas de remarketing para usuarios que abandonan el carrito.
