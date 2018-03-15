 # Ejercicios cortos
Bienvenidas al repositorio de ejercicios cortos de maquetación para la fase de Formación continua del la promoción Clarke.

Semanalmente se irán añadiendo nuevos ejercicios durante los meses 1-2 de la formación continua.

## Los ejercicios
La estructura de un ejercicio será la siguiente:  
```
/eX
|- assets
|  |-img
|  `- guia-ejercicio-x.png
|- css
|- index.html
|- js
`- README.md
```

En cada ejercicio habrá un archivo `README.md` con la propuesta de ejercicio y una pequeña guía visual para resolverlo.
Según el caso, en la carpeta **assets/** incluiremos archivos necesarios para solucionar el ejercicio.

### Cómo trabajar con el repositorio
Cada alumna tendrá que hacer un `fork` del repositorio para duplicarlo en su usuario de GitHub.

Pero claro, este repositorio se actualizará con nuevos ejercicios así que seguiremos los siguientes pasos para poder actualizarnos la nueva versión:
1. Añadiremos el repositiorio original como un nuevo repo remoto, además de origin, lo llamaremos **upstream**. En la carpeta de nuestro repo clonado:
```
git remote add upstream https://github.com/Adalab/clarke-ejercicios-cortos-formacion-continua.git
```
2. De esta manera podremos lanzar un `git pull` a **upstream** (en lugar de a origin) y tener los últimos cambios del repositorio original:
```
git pull upstream master
```


> **Otra solución** es hacer un fork del repo de ejercicios, clonar los dos en el ordenador y, cuando haya nuevos ejercicios, actualizar el repo original y copiar las carpetas nuevas a nuestro repo forkeado

### Índice de Ejercicios
- [ ] E1: Firma de email
- [ ] E2: Icono de Instagram en CSS
- [ ] E3: Una historia de grids

## Notas finales
Estos ejercicios son totalmente voluntarios y hay reservado un espacio para dudas como viene explicado en la presentación de la [Formación continua, en el Gtibook del curso](https://adalab.gitbooks.io/curso-programacion-front-end-2018/content/formacion-continua/0_presentacion.html)
