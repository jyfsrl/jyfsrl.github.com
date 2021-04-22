# Instrucciones para actualizar precios

1. Iniciar sesión en Github.com

2. Entrar al link https://github.com/jyfsrl/jyfsrl.github.com

3. Hacer click en index.html
![alt text](instrucciones/inicio.png "Inicio de repositorio, hacer click en index.html")

4. Hacer click en el ícono de editar (un lápiz como se ve en la imagen)
![alt text](instrucciones/editar_index.png "Hacer click en editar")

5. Ir hasta donde dice "ACTUALIZAR PRECIOS AQUÍ" (alternativa: ctrl+F para buscar el 
texto).

6. Para cambiar precios de ítems ya existentes, basta con cambiar el precio que se ve 
debajo de cada ítem como se muestra en la imagen.
![alt text](instrucciones/modificar_precio.png "Basta con cambiar el precio debajo del ítem")

7. Para añadir un nuevo ítem, copiar y pegar el siguiente código después de cualquier
\\</tr>, reemplazando con el nombre del producto y el precio con el símbolo $.

<tr>
	<td>Nombre del nuevo ítem</td>
	<td>$XXX</td>
</tr>

![alt text](instrucciones/agregar_items2.png "Copiar y pegar estas 4 líneas de código, luego cambiar datos del ítem.")

8. Para eliminar un ítem, borrar las 4 líneas de código desde \<tr> hasta \<\tr>.
![alt text](instrucciones/agregar_items1.png "Eliminar estas 4 líneas de código para eliminar un ítem.")

9. Guardar cambios haciendo un commit. Escribir un título y comentario para indicar los 
cambios realizados y hacer click en el botón verde "Confirmar cambios".
![alt text](instrucciones/guardar_cambios.png "Confirmar cambios.")