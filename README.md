# 📊 Data Science Challenge 1 - Análisis de Tiendas

Este proyecto de Data Science presenta un estudio detallado de cuatro tiendas pertenecientes al cliente **Juan**, con el objetivo de evaluar su desempeño y tomar decisiones estratégicas basadas en datos.  

> **Conclusión principal**: Se recomienda **vender la Tienda 3** debido a su bajo rendimiento comparativo.

---

## 🧠 Contenidos del análisis

Se abordaron distintos aspectos clave del negocio, incluyendo:

- **Facturación**: Comparación de ingresos entre tiendas.
- **Ventas por categoría**: Análisis del comportamiento de productos según categoría y tienda.
- **Costo promedio de envío**: Evaluación del gasto logístico por tienda.
- **Productos más y menos vendidos**: Identificación de top y bottom sellers por tienda.
- **Eficiencia de envío**: Estudio geográfico mediante coordenadas de envío.
- **Calificación promedio de productos**: Valoración de los productos según la opinión de los clientes.

---

## 🛠️ Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib

---

## 🚀 Instrucciones de uso

1. **Clona este repositorio:**

   ```bash
   git clone https://github.com/cristianjosepaz/alura_store_latam.git
2. **Abre el notebook en Google Colab**

    Puedes subir el archivo `.ipynb` directamente a [Google Colab](https://colab.research.google.com/) o abrirlo desde tu Google Drive.

3. **Carga los datasets**

    Asegúrate de cargar los archivos necesarios si se solicitan (puedes usar el entorno de archivos de Colab o montarlo con Google Drive).


4. **Ejecuta el notebook paso a paso**

    Corre cada celda para reproducir el análisis, visualizaciones y conclusiones.

---

## 📌 Notas

- El análisis es completamente reproducible en Google Colab.
- No se requiere instalación de librerías adicionales fuera de las incluidas por defecto en Colab (Pandas y Matplotlib).
- Las visualizaciones fueron diseñadas para facilitar la toma de decisiones estratégicas.

---

## 📈 Resultado final

Del análisis general se observa que la Tienda 1 es la que mayor contribución realiza a las ganancias totales, representando el 26%, apenas por encima del resto de las tiendas (25%, 24% y 23%). En términos de volumen e impacto comercial, su desempeño es comparable al de las demás, y no presenta diferencias relevantes en la composición de productos más vendidos, menos vendidos ni en la distribución por categorías.

Sin embargo, al profundizar en los indicadores operativos aparecen señales claras de alerta. La Tienda 1 tiene el mayor costo de envío promedio y, tanto en el análisis agregado como en el geográfico por punto de venta, muestra el peor rendimiento en eficiencia de envíos. Esta menor eficiencia coincide con su peor calificación de satisfacción al cliente, lo que sugiere una relación directa entre desempeño logístico y percepción del servicio.

En otras palabras, la tienda que más aporta en términos de ingresos es también la que presenta mayores debilidades operativas. Su liderazgo parece estar sostenido principalmente por volumen, no por eficiencia. Esto implica que, aunque actualmente su impacto global es similar al de las demás, su rentabilidad podría estar siendo presionada por costos logísticos elevados y por una experiencia de entrega menos favorable.

La conclusión es que el principal diferencial negativo de la Tienda 1 no está en la oferta comercial, sino en la gestión de envíos. Optimizar este componente tendría un efecto relevante tanto en margen como en satisfacción del cliente, especialmente considerando el peso que esta tienda tiene dentro del resultado total.
