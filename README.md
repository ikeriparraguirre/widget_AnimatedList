# AnimatedList - Iker Iparraguirre
Partiendo del ejemplo del widget que nos proporciona Flutter he creado la siguiente aplicacion.
![](demo.PNG)
# Funcionamiento del widget
Este widget es un contenedor que anima los elementos cuando se insertar o se eliminan. <br>
El AnimatedList se declara de la siguiente forma:
```
AnimatedList(
    key: _listKey,
    initialItemCount: _list.length,
    itemBuilder: _buildItem,
)
```
Aqui, la key rea un contenedor de desplazamiento que anima los elementos cuando se insertan o eliminan. <br>
El initialItemCount es el numero de items con el cual va a empezar el AnimatedList. <br>
Y el itemBuilder es la llamada a la funcion para crear cada item.
# Funcionamiento del ejemplo
Como se puede observar en la imagen inicial, esta es la aplicacion que he creado para mostrar el funcionamiento de AnimatedList. <br>
Al ejecutar, se muetra un elemento ya creado, pulsando sobre el boton "+" se crean nuevos elementos con el nombre "Elemento Nº " + el numero de elemento. <br>
Si pulsamos sobre un elemento se podra observar que cambia el color del texto a verde y que a la derecha cambia el mensaje "Elemento seleccionado: " al elemento seleccionado. <br>
Para eliminar un elemento habra que seleccionar el elemento y despues pulsar sobre el boton de "-".
## [Repositorio de GitHub](https://github.com/ikeriparraguirre/widget_AnimatedList)

