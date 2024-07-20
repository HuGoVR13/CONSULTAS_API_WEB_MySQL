# CONSULTAS_API_WEB_MySQL

# Estructura Del Projecto:

Clases y modelos que lo componen...

![image](https://github.com/user-attachments/assets/2d3da781-e63d-47d2-a5ae-903826268244)



# Clase Controlador:

Contiene cada Mapping y Endpoints que procesaras las respuestas Http

- /Api/Productos: Listara todos los productos que contenga nuestra base de datos

- /Api/Productos/Id: Buscara el producto por su numero Id

- /Api/Productos/search: Buscara el producto por el nombre que especifiquemos

- /Api/Productos/searchbyPrecio: Listara los productos en un rango de menor precio a mayor precio que digitemos


![image](https://github.com/user-attachments/assets/1c00e2dc-9edc-49a9-9c13-6df7c1286850)




# Clase Producto:

La clase producto donde asignamos los campos de nuestros atributos y contruimos sus setters and getters que nos facilitaran el uso de una arraylist.


![image](https://github.com/user-attachments/assets/53c5436b-5c73-4aff-a50f-4386b901d431)




# Clase Repositorio y Servicio:


![image](https://github.com/user-attachments/assets/879b9d37-b64a-4dad-82f8-9300621ffe52)






# Configuracion para la base de datos:

En propiedades de la aplicacion, realizamos la correcta conexion a nuestra base de datos MySQL, poniendo los campos como url, contrasela, usuario, etc. Para asi facilitar la interaccion.

![image](https://github.com/user-attachments/assets/44b55769-98b6-426a-9076-19890b430e6b)


# Datos MYSQL:


![image](https://github.com/user-attachments/assets/70603bb4-5af8-45d9-98a5-4779d65f33ae)





# Base de datos que se utilizo:

Se uso My SQL Worckbench como gestor para realizar nuestro esquema:


![image](https://github.com/user-attachments/assets/933ccda4-72cc-4426-bf82-93c29c2c8bba)







# Ejecucion y Pruebas en Web y Postman

# - Lista de productos:


![image](https://github.com/user-attachments/assets/d777fc56-fae5-4fdc-9b46-852426427133)



# - Buscar por Nombre:


![image](https://github.com/user-attachments/assets/0ed376b6-7786-4d3e-bbfe-e0716236b97c)



# - Buscar por numero de Id:


![image](https://github.com/user-attachments/assets/e9b4f24d-8db6-401d-be92-8c69a9d66624)



# - Buscar por precio de rango mayor a menor:


![image](https://github.com/user-attachments/assets/3ea3ab7d-a0b6-4e56-904f-b06037b0e4ab)


