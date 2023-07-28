Para acceder al DOM de HTML usamos el objeto llamado 'document' que nos permite acceder a todos los elementos
que contenga nuestra estructura HTML

Para acceder usamos un metodo del objeto 'document' llamado 'querySelector' y aqui le podemmos pasar como
argumento una clase, id, bloque, etcetera 

Si queremos acceder a una bloque que contenga una clase usamos 'document.querySelector(".")' colocamos un punto
y luego colocamos el nombre de la clase

Si queremos acceder al contenido de un elemento podemos utilizar: 'document.querySelector(".").textContent'

Ahora queremos seleccionar un elemento de nuestro HTML en este caso el boton de agregar tarea, si bien podemos seleccionar
en javascript utilizando las clases y los id pero puede surgir el caso de que alguien le cambie el nombre al atributo para 
eso tenemos otra opcion que se llama data-atributes

Para obtener la informacion del objeto que se esta generando podemos acceder  a ellos mediante parametros
Una forma para hacer que nuestro codigo en JS sea mas optimo es utilizando las funciones flechas o las funciones anonimas


btn.addEventListener "click", function (evento) => funciones normales
btn.addEventListener "click", (evento) => arrow function