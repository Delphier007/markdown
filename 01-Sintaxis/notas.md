# Esto es un h1
## Esto es un h2
### Esto es un h3 (y así hasta el 6)

Esto es un párrafo. No hay que escribir nada solo separlo por una línea en blanco. Si dejamos un SOLO ESPACIO y damos un retorno de carro sigue siendo el mismo párrafo y la misma línea.  
Pero si dejamos 2 ESPACIOS Y UN RETORNO DE CARRO estamos en el mismo párrafo pero con salto de línea


Para que se genere otro párrafo distinto, dejamos dos líneas entre ambos

Para generar listas desordenadas podemos utilizar *, + y -

* Generado con *
+ Generado con +
- Generado con -
  * Subnivel con un TAB
  * Subnivel con un TAB

Las listas ordenadas se generan numerando con el número y un punto detrás.

1. Uno
2. Dos
3. Tres
   
    1.1. Subnivel (con 4 espacios o 2TABs porque yo lo tengo configurado en VS Code como TAB=2 espacios)
    1. Subnivel
        * Se pueden combinar listas sin ordenar y ordenadas
        * En esta vamos a hacer otro nivel ordenado
    1. Con más subniveles ordenados
        1. Otro elemento
        2. Otro más
            1. Otro subnivel más
          1. Y otro más


4. Aunqeu escriba un 1 NO comienza por 1 si no que sigue por 4. Se utiliza un comentario para reiniciar contador.

<!-- Los comentarios se utilizan para reiniciar las listas numeradas -->

1. Otra lista (los comentarios se utilizan para reiniciar la numeración de las listas)
2. Otra más

        2.1. Holas

        2.2. Dos
3. Tres
4. Cuatro

          .container {
                Color: #ccc;
                font: 'arial';
            }
5. Cinco

    5.1. Hola
    5.2. Adiós

6. Seis
7. Siete
1. Hola
<!-- Comentario -->


