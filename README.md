El proyecto consiste en desarrollar un servidor basado en Express que permita hacer consultas a un archivo JSON que contiene información de productos. Para manejar la información de los productos se utiliza una clase llamada ProductManager que se encarga de leer y escribir en el archivo JSON.

El servidor tiene dos endpoints:

1. Ruta /products que devuelve todos los productos en formato JSON. Esta ruta puede recibir un query param limit que indica el límite de resultados que se quieren obtener.

2. Ruta /products/:pid que devuelve un producto específico. El id del producto se debe pasar como parámetro en la URL.

El proyecto se compone de varios archivos:

app.js: Archivo principal del servidor Express. En este archivo se definen los endpoints y se inicia el servidor.

productManager.js: Archivo que contiene la clase ProductManager que se encarga de manejar los productos y el archivo JSON.

productos.json: Archivo JSON donde se almacenan los datos de los productos.
