El código fuente está en la siguinete URL:

https://colab.research.google.com/drive/1j-BLBG6vgXuouAjLLTKljmqd2JfjFXLA

![code1](exploration-data-code-1.png)
![code2](exploration-data-code-2.png)

![result1](exploration-data-result-1.png)
![result2](exploration-data-result-2.png)
El gráfico muestra una distribución de precios, donde la mayoría de los productos se concentran entre precios bajos y medios. Existen pocos productos con precios altos, lo cual indica una distribución sesgada hacia precios económicos.
![result3](exploration-data-result-3.png)
Este gráfico permite identificar las categorías con mayor valor total en precios. Las categorías con barras más altas son las que contienen productos más costosos o en mayor cantidad dentro del catálogo.
![result4](exploration-data-result-4.png)
Este gráfico de caja y bigotes muestra la variabilidad de precios según el material. Los materiales como 'Silk' y 'Wool' presentan precios más altos y una mayor dispersión, mientras que materiales como 'Nylon' y 'Cotton' se concentran en precios más bajos.

# **Análisis del Gráfico de Distribución de Precios por Material (boxplot)**

## **Descripción del gráfico**
- **Eje X:** Contiene los diferentes tipos de materiales de los productos, como `Cotton`, `Silk`, `Wool`, `Nylon`, etc.
- **Eje Y:** Representa los precios de los productos asociados a cada material, con valores en una escala continua.

## **Elementos del gráfico**
- **Caja (Box):** Muestra el rango intercuartílico (IQR), que contiene el 50% de los datos, desde el primer cuartil (Q1) al tercer cuartil (Q3).
- **Línea dentro de la caja:** Es la mediana (Q2), el valor central de los precios para cada material.
- **Bigotes (Whiskers):** Extienden el rango para incluir los precios que no son valores atípicos.
- **Puntos fuera de los bigotes:** Representan valores atípicos, es decir, productos con precios considerablemente diferentes del resto.

## **Análisis detallado**
- **Materiales de alto costo:** `Silk` y `Wool` presentan una mediana de precios más alta y una mayor dispersión, lo que indica productos de mayor valor. Los bigotes largos sugieren que algunos productos en estos materiales tienen precios aún más elevados.
- **Materiales económicos:** `Cotton` y `Nylon` tienen precios más concentrados, con cajas más estrechas y valores en el rango bajo del eje Y, lo que sugiere productos más accesibles y homogéneos en precio.
- **Valores atípicos:** Los puntos dispersos por encima de los bigotes en `Silk` y `Wool` indican productos con precios excepcionalmente altos, posiblemente artículos de lujo.

## **Conclusiones**
1. Los materiales influyen significativamente en el precio de los productos.
2. Materiales premium como `Silk` y `Wool` presentan una amplia gama de precios y tienden a tener valores elevados.
3. Materiales más comunes como `Cotton` y `Nylon` son más asequibles y tienen precios consistentes, lo cual puede ser ideal para productos en mercados de consumo masivo.
