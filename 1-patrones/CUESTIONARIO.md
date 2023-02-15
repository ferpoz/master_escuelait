# Prueba Patrones-UML

## Cuestionario de la Prueba Patrones-UML

1. Determina la corrección de los siguientes enunciados. En caso incorrecto, justifica la respuesta:
 * "la identidad identifica al ente o a la entidad";
 * "el identificador identifica al ente o entidad de cierta identidad";
 * "la entidad del ente es el identificador de la identidad"

 * R. "la identidad es el conjunto de valores o rasgos que identifican al ente o entidad"
 * R. "el identificador es el nombre o valor que nos permite identificar al ente o entidad de cierta entidad"
 * R. "La entidad o ente, son la misma cosa, son sinonimos. Si acaso son identificadores de algo más, de alguna otra cosa"

2. Escribe 3 urls de 2 imágenes recursivas (no un seguimiento de una ejecución) y de 1 imagen que sí lo parece pero que no lo es.

 [Imagen recursiva 1](https://1.bp.blogspot.com/_o284OFANU6E/S8n245h2p7I/AAAAAAAAABY/BE2AXEPhh2k/s320/sluggo_recursive.jpg)

 [Imagen recursiva 2](https://2.bp.blogspot.com/-e8a0N8jjIAE/XMmMTkWBTTI/AAAAAAAAATI/nKpdKwytUmoWeiYp8GuZcdIEsy8yFjyrACLcBGAs/s1600/recursivo.jpg)

 [Imagen no recursiva](https://www.istockphoto.com/es/vector/recursividad-de-la-abuela-se-sienta-en-la-silla-repetici%C3%B3n-de-la-abuela-mujer-y-gato-gm814763922-131882597?phrase=recursividad)

3. Describe la imagen de la documentación de la unidad "Patrones" del "recu"-árbol del parque

<picture>
    <img alt="Árbol recursivo" src="arbol.jfif">
</picture>

 * Se dibuja una rama.
 * A un tercio de la altura de la rama, se dibuja una rama de menor de tamaño y con un angúlo hacia la izquierda. 
 * A la mitad de la altura de la rama, se dibuja una rama de menor tamaño que la segunda rama y con un angulo hacia la derecha. 
 * Al final de la rama, se dibuja una rama de menor tamaño que la tercera rama y con un ángulo hacia la derecha. 
 * Se repiten los tres pasos anteriores con cada rama que se va dibujando.

4. Describe la suma de dos números enteros positivos de forma recursiva

 * suma(lista de n elementos)
    * si la lista de elementos esta vacía devuelve cero
    * en otro caso devuelve 
        * elemento 1 + sum(lista de los elementos sin el elemento 1)

5. Crítica el siguiente diagrama

* El nombre MDPS no es claro, hay que adivinar el significado. Quizá un mejor nombre es Curso o Master. 
* La clase MPDS (o Curso) debe estar arriba de la jerarquía.
* El Curso se compone de Unidades, la relación en el diagrama no lo indica así.
* Igualmente cada Unidad se compone de una o más prácticas.
* En general los nombres de las clases se definen en singular. Espectadores y Ejercicios deberían ser Espectador y Ejercicio respectivamente.

<picture>
    <img alt="Vocabulario de prácticas" src="diagrama_cuestionario_patrones.png">
</picture>