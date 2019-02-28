# WebTest
1.- Crear la solucion vacia.

2.- Crear el proyecto Net Core version 2.1 sin autenticación.

3.- Añadir el fichero .editorconfig para unificar la alineación de los ficheros.

4.- Añadir el fichero .gitignore
- Añadir los directorios obj y bin.

5.- Substituir bootstrap 3 por bootstrap 4
- Click derecho en el proyecto de la solución, "Administrar bibliotecas del lado cliente..."
- En el libman.json: añadir la libreria bootstrap 4 sin especificar los ficheros (rellenando solo provider, library y destination).
- Eliminar el directorio wwwwroot/lib/bootstrap.
- Compilar