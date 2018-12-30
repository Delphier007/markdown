# NOTAS-2
  Para esctibir fórmulas matemáticas se debe instalar un plugin con math. Por ejemplo: markdown-it-math. **
  
  $$\sqrt{c^2=a^2 + b^2}\div2\flat\sharp$$ 

## Seguimos con la SINTÁXIS de Markdown

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces intro)

Al igual que sucede con HTML, Markdown no soporta dobles líneas en blanco, así que si intentas generarlas estas se convertirán en una sola al procesarse.

Para realizar un salto de línea y empezar una frase en una línea siguiente DENTRO DEL MISMO PÁRRAFO, tendrás que pulsar dos veces la barra espaciadora antes de pulsar una vez intro.

"Andando con sus patitas mojadas,  
el gorrión  
por la terraza de madera"


Si lo intento sin los espacios en blanco

al final no funciona. Ver código HTML

      <p>"Andando con sus patitas mojadas,<br>
      el gorrión<br>
      por la terraza de madera"</p>

      <p>Si lo intento sin los espacios en blanco</p>
      <p>al final no funciona. Ver código HTML</p>

### Esto es un H3
###### Esto es un H6

## Esto es un H2 subrayado con una línea (guiones)

---

### Esto es un H3 subrayado con dos líneas (símbolo igual) - NO FUNCIONA???


*** 
* * *
Las líneas horizontales se forman con 3 o más símbolos:
asteriscos, guiones o guiones bajos.
- - -
---
Si los separamos con un espacio también sirve.
___
_ _ _

## CITAS

> Las citas se crean con el símbolo
> MAYOR QUE colocándolo al principio de
> cada una de las líneas de la cita. Esto genera
> un ***blockquote***
> 
> > Esto es una cita anidada a la principal
> 
> Esta no está anidada.

## Código de bloque PRE + CODE
~~~
  Código de bloque.
  Se pueden añadir tantas líneas y párrafos como se quiera.

  Tenemos estas líneas de ejemplo.
~~~

      Tenemos el mismo efecto con 3 TABs
      Como se puede ver en este ejemplo

También se puede hacer con tres backticks. A los bloques de código se les puede indicar el lenguaje para que lo coloree. En nuestra página tendremos que instalar algún plugin en JS para que lo coloree según el lenguaje.

```javascript
const holaMundo = () => "Hola mundo"
```

```css
body {
      background: #ccc;
      font-size: 2rem;
}
```

Una de las razones para utilizar bloques de código con MD es que si quisiéramos escribir un tutorial de HTML el navegador lo interpretaría como código de la propia página.

````html
<!doctype html>
...
<p class="principal">lorem ipsum</p>
````


## Código solo con CODE
`Para texto entre etiquetas CODE usamos  back ticks`

### **Negritas** y *cursivas*
#### __Negritas__ y _cursivas_
##### ***Combinado***      

- - - 

## ENLACES
### Enlaces en línea

SEGUIMOS POR LOS ENLACES EN LA PÁGINA SIGUIENTE: [Enlace](https://markdown.es/sintaxis-markdown/)

[Este enlace a _blank NO FUNCIONA!](http://google.com){:target="_blank"}
***
<a href="https://google.es" target="_blank">Ir a Google</a>

***

### Enlaces por referencia (cuando son muchos o muy largos)

Lorem ipsum dolor sit [enlace] amet consectetur adipisicing elit. Enim dolorum et quos [otro][enlace] nesciunt perspiciatis veritatis iure sapiente, nostrum omnis nihil accusantium id, [más][enlace] aliquam deserunt eos placeat expedita, [enlace] aperiam rerum eveniet!

<!-- Al final de la página se suelen poner los enlaces referenciados.
Como se puede ver en el primer enlace, al ponerlos juntos el enlace OTRO referencia a ENLACE -->

[enlace]: https:google.es

### Enlaces automáticos

Es cuando quieres que el enlace no se enmascare en otra palabra, si no que aparezca tal cual. Por ejemplo: <https://google.es>

___

## IMÁGENES

Insertar una imagen es idéntico a los enlaces pero con el símbolo de `!` al principio del enlace.

![Texto alternativo para la imagen](https://picsum.photos/800/100 "Título al poner el ratón sobre la imagen")

### Imágenes por referencia.

Para que la escritura sea más limpia, podemos utilizar el mismo método que para los **links**: por referencia.

![Texto alternativo][img1]

[img1]: https://picsum.photos/800/300?random "Título alternativo" 

## ESCRIBIR CARACTERES ESPECIALES (asterisco, guiones, almohadilla, etc...)

Lo haremos insertando la `\` delante del símbolo en cuestión. Por ejemplo podemos esctibir la \#

<p class="clase">
Para escribir párrafos con una clase asignada tendremos que insertar HTML directamente en el MD.
</p>

## TABLAS

Para las tablas utilizamos tres guiones para cada campo separados con un PIPE `|`. Los pipes de inicio y final no hacen falta pero son más estéticos. Con los `:` alineamos.

|Campo 1 | Campo 2 | Campo 3|
|:---|:---:|---:|
Texto 1 | 12/10/2008 | 25,30 €
Otro texto | 01/12/2009 | 15,25 €
Último texto | 25/03/2012 | 7,15 €
