# Solucion de la Tarea de la Unidad 2

**Primero se le pregunta al usuario que ingrese el numero de un mes, luego se almacena en la variable mes**

> var mes = prompt("Ingrese el numero de un mes"); 

**Luego se crea una condicional que verifica si el valor almacenado en la variable mes es igual o mayor a 1 o igual o menor a 12, si es menor que 1 y mayor a 12, muestra el mensaje "valor invalido"**

> if (mes < 1 || mes > 12){
>  alert("Valor invalido")
> }

**Si el numero es valido, se ejecuta el codigo del else, donde hay mas condicionales**

> else{
  
**Si el numero almacenado en la variable mes es igual o mayor a 1 Y menor o igual a 3, muestra el mensaje "Es invierno"**

>  if (mes >= 1 && mes <= 3){
>    alert("Es invierno")
>  }

**Sino, Si el numero almacenado en la variable mes es igual o mayor a 4 Y menor o igual a 6, muestra el mensaje "Es primavera"**

>  else if (mes >= 4 && mes <= 6){
>    alert("Es primavera")
>  }

**Sino, Si el numero almacenado en la variable mes es igual o mayor a 7 Y menor o igual a 9, muestra el mensaje "Es verano"**

>  else if (mes >= 7 && mes <= 9){
>    alert("Es verano")
>  }

**Sino, Si el numero almacenado en la variable mes es igual o mayor a 10 Y menor o igual a 12, muestra el mensaje "Es otono"**

>  else if (mes >= 10 && mes <= 12){
>    alert("Es otono")
>  }
  
>}

**Por ultimo muestra una alerta con el nombre y numero de carné**

> alert("Diego 22011393");