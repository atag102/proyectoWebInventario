# proyectoWebInventario                                                                                                                 Este enunciado puede sufrir modificaciones
Nuestro cliente quiere que se cree una pagina web en la cual se puedan registrar usuarios comunes y que exista un solo usuario administrador (el cual es nuestro cliente).Cuando el usuario comun intente registrarse en el sistema este le pedira que llene el formulario con los siguientes datos :

*Nombre                                                                                                                                   
*Apellido                                                                                                                                 
*CI(cedula de identidad)
*Fecha de nacimiento                                                                                                                       
*Direccion                                                                                                                                 
*Correo electronico                                                                                                                       
*telefono                                                                                                                                 
*username                                                                                                                                 
*contraseña

El usuario comun podra ver los diferentes productos que nuestro cliente esta vendiendo en su negocio, se dividiran los productos en 3 diferentes tipos: 

a)productos de limpieza para la casa.                                                                                                     
b)productos de maquillaje.                                                                                                                c)productos de higiene personal.                                                                                                          d)Tintes para el cabello.                                                                                                                                                                                                                                                       
Entonces cuando un usuario comun se ubique en un tipo de producto de los antes mencionados este va a listar todos los productos disponibles de ese tipo.

Ahora el usuario administrador podra realizar un inventario completo sobre su negocio las siguientes operaciones que podra realizar un usuario administrador son:

   *Agregar un producto para la venta:Cuando nuestro usuario dese agregar un producto del tipo a),b) o c) pirmero debera llenar este formulario:
         
1)Descripción.                                                                                                                 
2)Peso.                                                                                                                          
3)Marca.                                                                                                                       
4)Color.                                                                                                                                5)RIF                                                                                                                                   6)Tipo de producto                                                                                                                      7)Cantidad.                                                                                                                              8)Costo.                                                                                                                                9)Precio venta.                                                                                                                          10)Distribuidora.                                                                                                                                                                                                                                                               Por supuesto antes el usuario administrador podra definir el IVA con el cual va a trabajar.El precio venta sera calculado por el sistema y no sera necesario calcularlo antes.Mientras que para productos del tipo d) se llena este formulario:
         
1)Descripción.                                                                                                                 
2)Peso.                                                                                                                         
3)Marca.                                                                                                                      
4)Color del tinte.                                                                                                                      5)RIF                                                                                                                                    6)Tipo de producto                                                                                                                      7)Cantidad.                                                                                                                              8)Costo.                                                                                                                                9)Precio venta.                                                                                                                          10)Distribuidora.                                                                                                                        11)Numero del tinte.
         
*Vender producto:A la hora que un usuario quiere comprar uno o varios producto se tendra que llenar el siguiente
forlmulario:                                                                                                                                                                                                                                                                 1)RIF.                                                                                                                                   2)Cantidad a vender.                                                                                                                     3)precio unitario.                                                                                                                       
4)IVA.                                                                                                                                   
5)Precio total a vender                                                                                                                                                                                                                                                         El usuario deberia se capaz de agregar varios articulos de diferentes tipos cuando se esta vendiendo.                                                                                                                                                                            *Buscar producto:En el momento que el usuario acceda a esta seccion se le pedira como se realizara la busqueda del producto si sera por RIF,descripcion,Marca,Distribuidora,Numero de tinte o color del tinte despues de definir el modo de busqueda este realizar su busqueda y listara todos los diferentes resultados que se consiguieron.

----------------------------------------------------------------------------------------------------------------------------------------Herramientas a utilizar para este proyecto:

  *El framwork AngularJS
  *Python
  *MySql o mongoDb
----------------------------------------------------------------------------------------------------------------------------------------
