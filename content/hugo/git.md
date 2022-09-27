---
title: "Git"
date: 2022-09-27T19:52:53+02:00
draft: false
---

# Repositorio en github
## Crear un repositorio nuevo y ligarlo al local
1. Accedemos a github con nuestro usuario y password
2. En nuestra cuenta creamos un repositorio
3. En este momento nos mostrará la página una serie de comandos que hay que ejecutar en local. Las acciones son:
   4. Vamos a local al directorio donde está nuestro proyecto
      5. ejecutamos
      6. ```bash
      7.   git init  # este comando incializa nuestro directorio como un proyecto de git . Habrá crado un directorio llamado .git 
      9. ```
      
         ```bash
         git add .  # con este comando añadimos los ficheros de mi directorio (todos por especifica .) al repositorio 
         ```main

         ```bash
         git commit -m "mensaje de checkpoint" .  # con este comando especificamos un mensaje para los cambios actuales 
         ```
        ```bash
       git branch -M main  # Creamos una rama o directorio de trabajo asociado a el repositorio local 
       ```
      
```brach
git add remote origin https://github.com/MAlejandroR/ #Ligamos el repositorio local al repositorio remoto
```

```brach
git push origin main # Sube los ficheros añadidos al remoto


```

### copiar un proyecto en otro destino

1. Accedo a git hub y copio la url del repositorio 
2. escribo
```bash
git clone "la url"  # creará un directorio con el nombre del proyecto y todo el contendo
``` 
3.- trabajo normal y al final hago un push

```bash
git add *
git commit -m "nuevos cambios"
git push -u origin main # Con esto acutalizaré el proyecto en github con los últimos cambios
``` 

### Actualizando un proyecto modificado en otro lugar
*Acualizo el proyecot en local con el remoto
```bash
git pull
``


      

      


