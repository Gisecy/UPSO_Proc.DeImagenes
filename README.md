# UPSO_Proc.DeImagenes
Procesamiento de Imágenes en Python

Proyecto 2 - Procesamiento de Imágenes

1. Una empresa está desarrollando una red neuronal capaz de identificar señales de
tránsito. Es necesario normalizar las imágenes del dataset para que tengan la misma
dimensión (tamaño).

a) Escribir una función que reciba como parámetros dos strings, uno contendrá la
ruta para acceder a una imagen, y el otro una palabra clave, que podrá ser “Youtube,
Instagram, Twitter o Facebook”. La función debe redimensionar la imagen al tamaño
adecuado especificado como parámetro para cada una de las palabras clave
(busque las dimensiones recomendadas de cada aplicación).

b) Una vez que la red neuronal comenzó a dar sus primeros resultados, el cliente
pidió un reporte de avances en el que quiere comparar la imagen original con lo que
identificó la red. Diseñar una función que a partir de las rutas de dos imágenes, las
ajuste (mismo tamaño) y las muestre enfrentadas.

3. Seleccionar una imagen de su agrado, y generar otras 9 aplicando cada uno de los
filtros de los siguientes filtros de Pillow. Mostrar y guardar el resultado de cada una.

ORIGINAL BLUR

CONTOUR DETAIL

EDGE ENHANCE EDGE ENHANCE MORE

EMBOSS FIND EDGES

SHARPEN SMOOTH

5. Cree una función que ajuste el contraste de una imagen utilizando su histograma.
Probala con una imagen oscura.

6. Su equipo de trabajo está creando una aplicación en Python para asistir a pintores y
dibujantes. Le han solicitado a usted programar una función que a partir de una foto
de una persona, ayude a los clientes a dibujar el boceto de la persona de la foto.
Pruebe su función con una foto de su elección.

Ejemplo: ver link al final del readme

7. Se desea separar de una imagen satelital máscaras para aislar (resaltar en color)
lotes de un campo. Esto puede lograrse utilizando máscaras binarias a partir de la
conversión de una imagen RGB a formato ‘L’ (escala de grises). El código para
hacer esto se vio en la clase de consulta y está disponible en Moodle.
Sobre el final del código se muestra como generar una máscara personalizada
utilizando “ImageDraw”. Esta máscara se genera con las coordenadas de las cuatro
esquinas del lote que deseamos resaltar. Luego se utiliza el método composite para
resaltar el lote deseado.

a) Analizar el código en su totalidad para tener un buen entendimiento del
funcionamiento y comentar cada uno de los bloques

b) Reutilizar el código de la última sección y escribir una función que tome
cuatro puntos indicados por el usuario y genere una máscara para mostrar
una parcela. Cuando hablamos de última sección nos referimos al apartado
“MOSTRAR UN CUADRANTE SELECCIONADO CON MASCARA
MANUAL”.

c) En cuanto tengan la función hecha y funcionando, modificarla para que
puedan mostrarse dos lotes coloreados en una misma imagen. Esto implica
dibujar dos regiones en la máscara antes de aplicarla, o generar una
máscara, aplicarla, luego generar otra máscara y aplicarla. Elegir la opción
que prefieran.

Imagen base: https://optiagro.com/wp-content/uploads/2018/06/lotes.jpg
