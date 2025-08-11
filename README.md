# Sorteador de Amigos 🎉

Este proyecto es una sencilla aplicación en JavaScript que permite agregar nombres a una lista de amigos y luego seleccionar uno al azar mediante un sorteo.

## 🧩 Funcionalidades

- Agregar amigos a una lista.
- Mostrar la lista de amigos en pantalla.
- Realizar un sorteo aleatorio para seleccionar un amigo de la lista.

## 🚀 ¿Cómo usarlo?

1. Escribe el nombre de un amigo en el campo de texto.
2. Haz clic en el botón **"Agregar"** para incluirlo en la lista.
3. Una vez agregados todos los amigos deseados, haz clic en **"Sortear"** para seleccionar uno al azar.
4. El nombre sorteado se mostrará en pantalla.

## 🛠️ Estructura del código

- `amigos`: arreglo que almacena los nombres ingresados.
- `agregarAmigo()`: función que valida y agrega un nombre a la lista.
- `mostrarAmigos()`: actualiza el DOM para mostrar la lista completa.
- `sortearAmigo()`: selecciona un nombre al azar de la lista y lo muestra en pantalla.

## 🖼️ Requisitos del HTML

Para que el script funcione correctamente, el HTML debe incluir los siguientes elementos:

```html
<input type="text" id="amigo" placeholder="Nombre del amigo">
<button onclick="agregarAmigo()">Agregar</button>

<ul id="listaAmigos"></ul>

<button onclick="sortearAmigo()">Sortear</button>
<ul id="resultado"></ul>
