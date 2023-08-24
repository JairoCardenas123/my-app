# Componentes en REACT

son unidades fundamentales que componen una interfaz de usuario,son bloques de construccion reutilizables.



```Un Componente Es Una FUNCION De JavaScript, Punto Clave```

*Devuelven codigo HTML 

 ejemplo
---------

```JavaScript
function ExpenseItem(){
    return <h2>Expense item!</h2>
}
```


# Los Componentes Se Anidan

colocar un elemento uno dentro de otro de manera jerarquica o estructurada

``` Por ejemplo: imagina que estás construyendo una aplicación de redes sociales. Puedes tener un componente principal llamado "Página de Perfil" que contiene varios otros componentes anidados, como "Información de Usuario", "Publicaciones Recientes" y "Lista de Amigos". Cada uno de estos componentes anidados a su vez podría contener más componentes más pequeños para representar elementos individuales.```


# Dentro De Un Componente Solo Debe Tener Una Raiz

Le facilita a React una actualizacion de interfaz cuando cambia el estado del componente
