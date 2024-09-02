Aquí tienes el contenido en formato Markdown para un archivo README.md:

# Scraper de Productos de Amazon

## Descripción

Este proyecto es una aplicación web que permite a los usuarios buscar y extraer información de productos en Amazon. Utilizando técnicas de web scraping, la aplicación recopila datos relevantes como título, precio, enlace y imagen de los productos, y ofrece una interfaz amigable para que los usuarios puedan realizar búsquedas y descargar los resultados en formato Excel.

## Características

- **Búsqueda de productos**: Los usuarios pueden buscar productos por palabra clave y aplicar filtros por categoría (como electrónica, libros, ropa, etc.) y orden (precio ascendente o descendente).
- **Visualización de resultados**: Los resultados de la búsqueda se muestran en tarjetas informativas con detalles del producto, incluyendo título, precio y enlace a la página de Amazon.
- **Modal de imagen**: Al hacer clic en la imagen de un producto, se abre un modal que muestra la imagen a tamaño completo.
- **Descarga en Excel**: Los usuarios pueden descargar los resultados de la búsqueda en formato Excel (.xlsx) para su uso posterior.

## Tecnologías Utilizadas

- **Express.js**: Framework de Node.js para crear la aplicación web y manejar rutas y solicitudes HTTP.
- **Axios**: Biblioteca para realizar solicitudes HTTP desde el servidor Node.js hacia Amazon.
- **Cheerio**: Biblioteca para analizar y manipular el HTML de las páginas de Amazon.
- **XLSX**: Biblioteca para crear y guardar archivos de Excel a partir de los datos recopilados.
- **EJS (Embedded JavaScript)**: Motor de plantillas para generar la interfaz web dinámica.
- **Bootstrap**: Framework CSS para estilizar la interfaz web.
- **Font Awesome**: Biblioteca de iconos para mejorar la apariencia de la aplicación.

## Estructura del Proyecto

El proyecto sigue esta estructura de archivos y directorios:

```
amazon-scraper/
├── views/
│   └── index.ejs
├── public/
│   └── styles.css
├── app.js
├── package.json
└── README.md
```

- `views/index.ejs`: Plantilla EJS que genera la página principal, mostrando el formulario de búsqueda y los resultados.
- `public/styles.css`: Archivo CSS que define el estilo de la interfaz web.
- `app.js`: Archivo principal de la aplicación Express.js, que contiene la lógica del servidor y las rutas.
- `package.json`: Archivo de configuración de dependencias y scripts de la aplicación.
- `README.md`: Documentación del proyecto.

## Instalación y Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/amazon-scraper.git
   ```

2. Instala las dependencias:

   ```bash
   cd amazon-scraper
   npm install
   ```

3. Inicia el servidor:

   ```bash
   npm start
   ```

4. Abre tu navegador y visita `http://localhost:3000` para acceder a la aplicación.

En la página web, los usuarios pueden:

- Ingresar una palabra clave para buscar productos.
- Seleccionar la categoría y el orden de los resultados.
- Hacer clic en el botón "Buscar" para ver los resultados de la búsqueda.
- Hacer clic en el botón "Descargar Excel" para descargar los resultados en formato Excel.

## Contribuir

Si deseas contribuir al proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama con tus cambios: `git checkout -b feature/mi-nueva-caracteristica`.
3. Realiza tus cambios y haz commit: `git commit -am 'Agrego nueva característica'`.
4. Sube tus cambios a tu fork: `git push origin feature/mi-nueva-caracteristica`.
5. Crea un nuevo pull request en el repositorio original.

Estamos encantados de revisar tus contribuciones y fusionarlas con el proyecto principal.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
