# **Posicionando cajas**


Muchos de nosotros de niños hemos jugado con cajas de todas las texturas, tamaños y colores. Siempre realizabamos juegos que se nos venian en mente. ¿Pero alguna vez pensaste en jugarlo en la computadora?. Mejor dicho hacerlo tu mismo.   
En este trabajo realizaremos posicionamiento de cajas de manera divertida y fácil. Manos a la obra.

## Objetivos
* Poder colocar las cajas en sus posiciones indicadas.
* Ponerle color a cada caja.
* Realizar desplazamiento con los elementos de la caja.
* Manejar las distintas medidas.

***
## Modelo
Para poder replicar las cajas se mostrara el modelo a replicar.  
[Cajas](https://fotos.subefotos.com/c0a08756744f401530d3eb8bb58c36e3o.png).

---
## Estructura del proyect
Esta conformada por una:
* Carpeta Posicionando cajas
* Carpeta css
* Un archivo Index
* Un archivo Info

---

## Estructura de un archivo Index

```` html

<html>
  <head>
    <title>Posicionando de cajas</title>
  </head>
  <body>

   cajas
   </body>
</html>

````

----
## Estructura de un archivo de css
---
```` css
/* Colocamos un titulo - tipo de letra*/
h1 {
  font-style: italic;
  font-family: fantasy;
  text-align: center;
  color: rgb(227, 117, 40);
  text-decoration:underline;
  font-size: 3rem;
}
/* Llamamos a la clase padre*/
.caja-padre {
  background-color: rgb(223, 10, 10);
  width: 30rem;
  height: 30rem;
  position: relative;
}
````
