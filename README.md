# ejercicio-git-branch
# Pasos

Crear un nuevo repositorio en GitHub Ve a GitHub y crea un nuevo repositorio con el nombre ejercicio-git-branch. Inicializa el repositorio con un archivo README.md básico con el título del proyecto.

Realiza una clonación del repositorio. Recuerda que debes utilizar git clone:
``` code
bae2@jpexposito-VirtualBox:~$ git clone https://github.com/mahoramas/ejercicio-git-branch
Clonando en 'ejercicio-git-branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.
```

Crea un nuevo brancho rama para los nuevos cambios que vas a introducir:
``` code
bae2@jpexposito-VirtualBox:~$ cd ejercicio-git-branch/
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch$ git checkout -b ejercicio1-branch
Cambiado a nueva rama 'ejercicio1-branch'
```
---
Añade la siguiente clase al repositorio:
``` java
 public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }     
 ```
```code
git status 
En la rama ejercicio1-branch
Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        ejercicio1.java

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
     git add  Ejercicio1.java 
     git commit -m "Se incluye el Ejercicio1.java"
[ejercicio1-branch 83ea3a1] Se incluye el Ejercicio1.java
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio1.java
```
 
