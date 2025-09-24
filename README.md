# SQL Business Analysis  

## Objetivo  
Aplicar **SQL y Python** para el análisis de datos empresariales.  
El proyecto se centra en la extracción, limpieza y manipulación de información con el fin de generar **insights accionables** que apoyen la toma de decisiones estratégicas en un entorno de negocio.  

## Sobre el Dataset  
El dataset contiene información de clientes, transacciones y ventas de una compañía ficticia.  
Incluye:  
- Identificación de clientes  
- Fechas y montos de las transacciones  
- Productos y categorías  
- Información geográfica  

Los datos fueron proporcionados con fines educativos para prácticas de análisis.  
 
## Guía de uso  
- [Notebook del proyecto](notebook_sprint_9.ipynb)  
- Requisitos: Python 3.9+, Pandas, NumPy, Matplotlib, SQLAlchemy 
- Ejecutar el notebook en Jupyter o Google Colab para reproducir el análisis paso a paso.  

## Conclusiones  
- El análisis confirmó que la rentabilidad global de las campañas fue negativa, con un ROMI de –61.7%.  
- Ninguna fuente de adquisición alcanzó la rentabilidad esperada; sin embargo, las fuentes **3 y 4** mostraron mayor potencial, con un LTV superior a 6 dólares y un ROMI menos negativo (–8% a –9%).  
- Al segmentar por dispositivo, **Desktop** superó a **Touch** en valor de vida del cliente (2.8 vs 2.0) y en rentabilidad, mostrando un mejor retorno en usuarios de escritorio.  
- Se recomienda **reorientar la inversión** hacia las fuentes 3 y 4, priorizar campañas en Desktop y suspender aquellas fuentes de adquisición que resultaron ineficientes.
