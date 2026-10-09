<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTVKWDJhSX2CRZbV5x_5DoX69rTfHMCxZqYeFU1kMc8wQ&s=10" alt="Logo" style="width: 30%; max-width: 200px;">
</p>

# Aprendiendo Git & Github
- Estos son los pasos para iniciar con Git
## Paso 1
- Inicializar el nuevo repositorio
```
git init
```
- Directorio de Trabajo donde se escribe el código
## Paso 2
- Enviar los nuevos archivos o archivos modificados al area de preparación
```
git add index.html
git add .
``` 
- El Area de preparación es donde se preparan los cambios 

## Paso 3
- Registrar una descripción del cambio realizado
```
git commit -m "proyecto base"
```


# Github

```
git remote add origin https://github.com/cchura94/url_repositorio.git
```

- Enviar los cambios al repositorio Remoto
```
git push origin master
```
------- 
#### EJEMPLO
- Copiar el archivo (.env.example) a (.env) y actualizar las credenciales