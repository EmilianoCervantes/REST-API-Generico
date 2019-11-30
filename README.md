# Server REST de pruebas

## Opción a) Pasos para su creación
1. Ir al directorio de un proyecto en la terminal
2. Correr \> npm init
3. Darle enter a todo
  - Se genera un package.json
4. npm install --save json-server
5. Abrir la carpeta en un editor de código
6. Crear un archivo llamado db.json
7. Borrar los scripts que estén - seguramente nada más está el de "test"
8. Crear un nuevo script:
 - "start": "json-server -p 3001 -w db.json"
 - Significado: correrá en el puerto 3001 "-p 3001"
 - Detecta cambios en el archivo "-w db.json"
7. En la terminal correr \> npm start

## Opción b) Pasos para su instalación
1. Bajar el proy de Git
2. Dar npm install
3. Editar el archivo db.json si se necesita
4. En la terminal correr \> npm start


# Librerías instaladas
1. json-server: https://github.com/typicode/json-server
