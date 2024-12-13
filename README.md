Resumen

En el contexto de las licitaciones públicas en Chile entre 2014 y 2023, las empresas buscan constantemente oportunidades para diversificar y aumentar su éxito en futuros procesos de licitación. Este estudio tiene como objetivo explorar cómo las empresas podrían utilizar modelos de machine learning para clasificar y evaluar automáticamente oportunidades de diversificación hacia rubros relacionados, basándose en el concepto de density relatedness. A través de un análisis planificado de datos históricos de licitaciones públicas, se desarrollaron metodologías para calcular estas métricas y se aplicó un modelo predictivo que permitirá identificar las mejores oportunidades de expansión. Se espera que los resultados demuestren que una alta density relatedness indica que el rubro potencial (r’) está estrechamente relacionado con los rubros actuales del proveedor, lo que sugiere una mayor probabilidad de éxito en la diversificación hacia ese rubro.

Conclusion

Este proyecto se enfocó en responder a la pregunta de cómo las empresas pueden utilizar modelos de machine learning para identificar oportunidades de diversificación hacia nuevos rubros en el contexto de licitaciones públicas chilenas. Basándose en datos históricos y la métrica density relatedness, se construyó un modelo que busca predecir casos exitosos de diversificación. Los resultados obtenidos nos permiten extraer conclusiones claras sobre las capacidades y limitaciones del enfoque propuesto.
Por un lado, el modelo demostró ser efectivo en términos generales, alcanzando un AUC-ROC de 0.9210, lo que indica una excelente capacidad para distinguir entre casos exitosos y no exitosos. Esto valida la utilidad de la métrica density relatedness como un indicador clave para evaluar qué tan conectados están los rubros actuales de un proveedor con aquellos hacia los que podría diversificarse. Empresas con altos valores de esta métrica tienen significativamente mayores probabilidades de éxito al entrar en nuevos mercados. Este resultado es consistente con la hipótesis inicial y resalta que la diversificación no es aleatoria, sino que está condicionada por factores estructurales y de proximidad.
Sin embargo, no todo fue completamente positivo. El modelo presentó dificultades notables debido al desbalance extremo en los datos. Aunque se lograron identificar correctamente el 49.8% de los casos positivos (recall), la precisión fue baja (4.88%), lo que significa que el modelo generó un alto número de falsos positivos. Este aspecto limita su utilidad como herramienta autónoma para decisiones finales y sugiere que se debe usar como un apoyo inicial para identificar posibles oportunidades, seguido de un análisis más detallado por parte del proveedor.
Además, se identificaron otras variables importantes más allá de density relatedness, como el monto total adjudicado al proveedor y su porcentaje de adjudicación, que también demostraron ser factores clave en la predicción del éxito. Esto indica que la diversificación está influenciada tanto por la experiencia previa como por la estructura del mercado. Aunque las métricas de teoría de grafos, como clustering coefficient o pagerank, tuvieron menor relevancia, aportaron una dimensión complementaria que podría explorarse más a fondo.
En resumen, este proyecto confirma que modelos de machine learning que incorporan density relatedness pueden ser herramientas útiles para guiar estrategias de diversificación, pero con limitaciones claras. El modelo es bueno identificando patrones generales y señalando oportunidades, pero requiere ajustes para ser más efectivo en reducir falsos positivos. Estos resultados deben interpretarse con precaución, reconociendo que no garantizan éxito absoluto, pero sí ofrecen un marco sólido para mejorar la toma de decisiones estratégicas.
Finalmente, este trabajo resalta la importancia de combinar datos históricos, análisis de redes y machine learning para abordar problemas complejos como la diversificación empresarial. Si bien hay margen de mejora, los resultados obtenidos representan un paso valioso hacia el uso de herramientas analíticas para maximizar las oportunidades en licitaciones públicas, sentando las bases para futuras investigaciones y aplicaciones más robustas.