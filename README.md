# Parcial-final
____________________________________________
# de que trata?
_______________________________________________
Esta aplicación fue desarrollada en Python para simular una tienda tipo Shein o Temu. Utiliza el patrón de arquitectura MVC, lo que permite organizar el código en capas: el modelo gestiona los datos, la vista presenta la interfaz al usuario y el controlador conecta ambos. La app permite realizar búsquedas, agregar productos al carrito, calcular el total, y finalizar o cancelar la compra. Está construida con la biblioteca gráfica Tkinter y lee los productos desde un archivo JSON, lo que hace el sistema dinámico y fácil de escalar.
__________________________________________________
# Que hace el programa ?
____________________________________
Simula una tienda virtual donde el usuario puede:

Buscar productos.

Ver el catálogo completo.

Agregar productos al carrito.

Ver el carrito y el total acumulado.

Finalizar la compra o limpiar el carrito.
______________________________________________
# Estructura del programa: Patrón MVC
El programa está organizado siguiendo el patrón Modelo-Vista-Controlador (MVC), que separa claramente las responsabilidades del código.
_______________________________________________________
# Modelo (modelo.py)
Se encarga de la lógica de datos.

Carga los productos desde un archivo productos.json.

Permite obtener todos los productos o buscar por nombre.
________________________________________________________
# Vista (vista.py)
Contiene la interfaz gráfica construida con tkinter.

Muestra los productos en un ListBox.

Incluye campos de búsqueda, botones de acción, y el carrito.
_____________________________________________________________

 # Controlador (controlador.py)
Es el puente entre la vista y el modelo.

Atiende los clics del usuario y toma decisiones:

Si haces clic en "Buscar", le pide al modelo los resultados.

Si haces clic en "Agregar", actualiza el carrito.

Si haces clic en "Finalizar compra", muestra el total y limpia el carrito.
_______________________________________________________________________________
# Archivo principal (main.py)
Junta todo:

Crea el modelo.

Crea la vista.

Conecta todo con el controlador.

Inicia el mainloop() de Tkinter.

______________________________________________________________________________
# ¿Qué funcionalidades tiene?
Buscar productos por nombre.

Mostrar el catálogo completo.

Seleccionar productos y agregarlos al carrito.

Ver todos los productos agregados y el total de la compra.

Finalizar la compra o limpiar el carrito.

________________________________________________________________________________
