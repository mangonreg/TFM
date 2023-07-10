# Estudio de conjuntos críticos asociados a autotopismos no triviales de cuadrados latinos de orden 6
El presente documento pretende dar una breve explicación sobre los algoritmos incluidos dentro del archivo: Cuadrados_Latinos_TFM_MGR.ipynb
Para poder abrir el archivo se recomienda el uso de SageMath 9.2 Notebook

**********************
* Objetivo Principal *
**********************

El objetivo principal de este trabajo consiste en demostrar formalmente que los resultados recogidos mediante el estudio estadístico realizado durante el desarrollo del TFG son correctos. Para ello se realizará un estudio exhaustivo para cada caso planteado en el archivo Resultados_Estudio_Estadístico.pdf, ayudándonos de algunos algoritmos propuestos en la siguiente sección.

****************************
* Algoritmos desarrollados *
****************************

1) existenDeMenorTamano(entradas, autotopismo, ordenCuadrado): Dada una serie de entradas, un autotopismo y el orden del cuadrado que se está estudiando (para nuestros casos siempre será 6), tiene la capacidad de determinar si dicho conjunto de entradas hacen que el cuadrado parcial obtenido a partir de ellas es únicamente completable o no. En caso de serlo, esta misma función estudia si existe algún subconjunto de menor tamaño incluido en el conjunto de entradas que se les pasa como parámetro que haga que el cuadrado sea únicamente completable.

*******************
* Recomendaciones *
*******************

A pesar de que el trabajo de código desarrollado quede resumido en la función anterior, esta se sostienen sobre diversas funciones plasmadas en el código del TFG desarrolado el curso anterior y que recomendamos encarecidamente que lea y estudie si desea comprender verdaderamente el funcionamiento de dicho programa. Todas estas funciones tienen anotaciones en el código para facilitar su entendimiento. No obstante, si le surge cualquier duda, puede contactar con el desarrollador a través de la siguiente dirección de correo: mangonreg@alum.us.es
