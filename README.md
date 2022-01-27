# Codigo 13

## Comando para GIT

```
git init
```
- Este comando solo se hace una vez por proyecto, srive para inicializar nuestro proyecto con git
- :eye: crear una :file_folder: carpeta oculta llamada ```.git```


```
git status
```
- Poder listar y ver si los archivos estan listos para subir
- :eye: en caso los archivos no esten listos se verán de color rojo y cuando lo esten serán de coloer verde.


```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guada en un stash

```
git commit -m "comentario"
```
- Crear un punto en la linea de tiempo :alarm_clock: de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github
