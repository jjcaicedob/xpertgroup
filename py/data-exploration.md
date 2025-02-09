El código fuente está en la siguinete URL:

https://colab.research.google.com/drive/1j-BLBG6vgXuouAjLLTKljmqd2JfjFXLA

![code1](exploration-data-code-1.png)
![code2](exploration-data-code-2.png)

![result1](exploration-data-result-1.png)
![result2](exploration-data-result-2.png)
El gráfico muestra una distribución de precios, donde la mayoría de los productos se concentran entre precios bajos y medios. Existen pocos productos con precios altos, lo cual indica una distribución sesgada hacia precios económicos.
![result3](exploration-data-result-3.png)
Este gráfico permite identificar las categorías con mayor valor total en precios. Las categorías con barras más altas son las que contienen productos más costosos o en mayor cantidad dentro del catálogo.
# **Análisis del Gráfico de Precio Total por Categoría**

## **Descripción del gráfico**
- **Eje X:** Muestra las distintas categorías de productos, como `Tops`, `Bottoms`, `Outerwear`, etc.
- **Eje Y:** Representa el precio total acumulado para cada categoría, calculado como la suma de los precios de los productos en esa categoría.

## **Elementos del gráfico**
- **Barras:** Cada barra representa el precio total acumulado de los productos en una categoría específica.
- **Altura de las barras:** Indica el valor total de los precios por categoría. Categorías con barras más altas tienen mayor valor en precios.

## **Análisis detallado**
- **Categorías con mayor precio total:** Las categorías con barras más altas indican una mayor cantidad de productos o productos de alto precio. Esto puede reflejar una oferta variada o una tendencia hacia productos costosos.
- **Categorías con menor precio total:** Las categorías con barras más bajas sugieren una oferta reducida o productos generalmente económicos.
- **Variabilidad:** Una distribución desigual de las barras sugiere que algunas categorías son más dominantes en términos de valor económico dentro del catálogo.

## **Conclusiones**
1. Las categorías de productos con mayores valores totales pueden representar una estrategia comercial basada en productos premium o en una oferta más amplia.
2. Las categorías con valores más bajos podrían ser una oportunidad para diversificar la oferta o aumentar el margen de ganancias.
3. Esta visualización permite identificar patrones clave para decisiones comerciales, como cuáles categorías necesitan más inventario o estrategias de pricing diferenciadas.

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
