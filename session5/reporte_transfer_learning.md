## Sesion 06 (tarea)
**1. ¿Qué es Transfer Learning?**
 Para mí, el Transfer Learning (ejemplo como analogia) es como cuando alguien que ya sabe manejar una bicicleta aprende a conducir una moto. No empieza desde cero porque ya entiende el equilibrio y 
las señales de tránsito. En inteligencia artificial, significa agarrar un modelo que ya fue entrenado por expertos con millones de datos o imágenes y "pedirle prestado" su conocimiento para que nos
ayude a resolver un problema nuevo y más pequeño sin tener que gastar meses entrenando una red desde cero.

**2. ¿Qué modelo usaste?**
 El modelo MobileNetV2, es muy popular porque es "liviano". Está diseñado para funcionar bien en dispositivos que no tienen muchísima potencia, 
como los celulares. Lo que hace es analizar las imágenes por capas , desde lineas y colores a formas mas complejas.

**3. Resultado de la predicción**
 Para la prueba, subí una imagen de un gato El modelo predijo que era un gato con una probabilidad muy alta. ¿Fue correcto? Sí, el modelo acertó rápidamente. Es interesante lo rápido que reconoce objetos
cotidianos con tanta precisión.

**4. Parámetros congelados vs entrenables**
 Al configurar el modelo, huboo una gran diferencia en los números:
Parámetros congelados: Son la gran mayoría lo que ya vienen aprendido del modelo base. En mi caso fueron varios millones. Estos no se tocan porque son el "conocimiento previo".

Parámetros entrenables: Son solo unos pocos miles. Estos corresponden a la última capa que se añadió para que el modelo se adapte a nuestra tarea específica.
Esta separación es genial porque permite que el entrenamiento sea súper rápido.

7. Mi opinión personal
Lo más sorprendente de la sesión fue darme cuenta de que no necesito una supercomputadora ni ser un genio matemático para crear algo que funcione. Ver cómo las neuronas se organizan solas en 
las capas para detectar formas me voló la cabeza. Me motiva mucho saber que podemos usar modelos que ya existen para resolver problemas reales de nuestro país de forma tan visual. Y seria increible poder 
desarrolar algo relacionado a este tema.

**5. Aplicación potencial en Bolivia**
 Identifiqué que el Transfer Learning podría servir para crear una aplicación que centralice y clasifique eventos culturales en mi departamento. El problema es que la información de talleres 
gratuitos y salidas de clubes está muy dispersa en redes sociales. Usando un modelo base de lenguaje (como BERT), podríamos entrenar a la IA con unos 2,000 anuncios locales para que reconozca
automáticamente qué eventos hay mañana en mi ciudad, separando los talleres de las ferias o conciertos.Y si me voy a lo ético, pueden haber eventos que el modelo pueda identificar pero estos ya sean 
realizados con otros propósitos malos por el autior del evento ,etc.

**6. Descripción de mi dataset (CSV)**
También completé mi archivo sesion3/mi_dataset.csv. Los datos que recolecté tratan sobre el precio de alquileres en diferentes zonas de Cochabamba. Incluí columnas como la Zona, el Precio en bolivianos y una descripción de las características (como número de dormitorios o si tiene garaje). Estos datos nos servirán en la Sesión 18 para hacer análisis con Pandas.

## Seccion extra 
También completé mi archivo sesion3/mi_dataset.csv. Los datos que recolecté tratan sobre el precio de alquileres en diferentes zonas de Cochabamba. Incluí columnas como la Zona,
el Precio en bolivianos y una descripción de las características (como número de dormitorios o si tiene garaje). 
