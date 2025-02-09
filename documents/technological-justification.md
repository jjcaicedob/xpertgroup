# **Justificación Tecnológica**

La arquitectura propuesta para la tienda de ropa en línea busca integrar almacenamiento, procesamiento de datos, y capacidades predictivas mediante una solución robusta y escalable en la nube, utilizando las siguientes tecnologías:

## **1. Almacenamiento y Procesamiento de Datos en la Nube (Azure)**
- **Servicio Utilizado:** Azure Data Lake + Azure Synapse Analytics  
- **Justificación:** Azure Data Lake permite almacenar grandes volúmenes de datos estructurados y no estructurados, mientras que Azure Synapse ofrece capacidades avanzadas de análisis en tiempo real. La elección de Azure como núcleo central garantiza una arquitectura escalable y segura.

## **2. Integración Multicloud (Azure + AWS)**
- **Servicios Utilizados:** Azure Functions + AWS Lambda  
- **Justificación:** El uso de ambas nubes mejora la disponibilidad y resiliencia de los servicios. Azure se encarga del núcleo de datos y aplicaciones, mientras que AWS proporciona funciones complementarias y redundancia operativa. Esta integración permite mayor flexibilidad para elegir los servicios más eficientes de cada plataforma.

## **3. Machine Learning (Azure Machine Learning)**
- **Justificación:** Azure Machine Learning facilita el entrenamiento y despliegue de modelos predictivos, garantizando integración nativa con los demás servicios de datos. Esto permite predecir precios de productos basados en atributos como marca, categoría, color, talla, material y precio.

## **4. Visualización de Insights (Power BI)**
- **Justificación:** Power BI permite una visualización clara y dinámica de datos comerciales. El equipo comercial puede tomar decisiones informadas basándose en insights visuales fáciles de interpretar.

## **5. Gestión de Roles y Accesos (RBAC)**
- **Servicio Utilizado:** Azure Active Directory (Azure AD)  
- **Justificación:** La gestión de roles basada en RBAC garantiza un control granular sobre los accesos a los recursos. Esto proporciona mayor seguridad, asegurando que solo los usuarios autorizados accedan a información crítica.

## **6. Contenedores y Despliegue (Azure Kubernetes Service - AKS)**
- **Justificación:** AKS permite el despliegue y orquestación de contenedores, facilitando la escalabilidad y portabilidad de la aplicación. Su integración con pipelines CI/CD en Azure DevOps permite flujos de despliegue ágiles.

---

Esta combinación tecnológica asegura una solución moderna y eficiente que responde a las necesidades comerciales de la tienda, garantizando escalabilidad, seguridad y capacidades avanzadas de análisis para mejorar la toma de decisiones.
