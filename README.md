# Proyecto_Final
Integrantes del proyecto:
  Ivy González. C.I: 29.8644.441
  Samuel Salázar. C.I: 28.468.819
  Hector Luna. C.I.:28.189.194
  ---
Este programa simula la compra y venta de grama artificial por metro al cuadrado, donde se encuentran dos tipos de usuarios, el cliente y el administrado.
  - En el area principal se le pediran los datos al cliente, si este no se ha registrado al sistema. 
  Una vez dentro, entra al area de venta, se le mostraran los productos disponibles, por default apareceran 4, adjuntados con su debido precio y descripcion del producto.
  Despues de haber seleccionado el producto que el cliente desea comprar, se le mostrara una factura en pantalla con sus datos y el producto comprado.
  Se removera del inventario la cantidad de productos comprados, y estos se guardaran en un archivo '.txt'.
  
  - En el area de administrador, solo se podra acceder a esta area rellenando las casillas 'Usuario' y 'Contraseña' con la palabra 'admin'.
  Una vez dentro, el administrador podra agregar nuevos productos al inventario con su nombre, precio y cantidad disponible del articulo agregado.
  Tambien podra agregar mas stocks a los articulos por default y a los agregados por el mismo administrador.
  ---
El programa contiene dos librerias, Tkinter y os.
Este esta estructurado por un menu, una tienda y el menu de administrador.
