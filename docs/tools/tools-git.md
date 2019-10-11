---
layout: default
title: Git
parent: Tools
nav_order: 1
---

# Comandos más usados

### **Create a new repository**
Crear un nuevo repositorio y ejecutar
```
    git init
```
para crear un nuevo repositorio git.

---

### **Checkout a repository**
Crear una nueva copia del trabajo de un repositorio local ejecutando
```
    git clone /path/to/repository
```
Cuando se usa un servidor remoto, se debe ejecutar
```
    git clone username@host:/path/to/repository
```

---

### **Add & commit**
Puedes proponer cambios ejecutando
```
    git add <filename>
    git add *
```
Este es el primer paso del flujo de trabajo de git. Para realizar el commit de los cambios ralizados se debe ejecutar
```
    git commit -m "Commit message"
```
Ahora el archivo del commit esta en la cabecera, pero ya no se encuentra en tú repositorio remoto

---

### **Pushing changes**
Tus cambios ahora se encuentran en el HEAD. Para enviar estos cambios a tu repositorio remoto se debe ejecutar
```
    git push origin master
```
Cambios a la rama master o ha cualquier rama.

---

### **Update & merge**
Para actualizar tu repositorio local con el commit más reciente, se debe ejecutar
```
    git pull
```

---

## **More info** 
[Git - guide](https://rogerdudler.github.io/git-guide/)