# Comandos de Git

> 📌 Comandos más frecuentemente usados para git y github

---

## 🧩 Inicialización y conexión

```bash
git init
```

🔹 Inicializa un nuevo repositorio de Git en la carpeta actual.

```bash
git clone https://github.com/mckateturry/proyecto.git
```

🔹 Clona un repositorio remoto en la carpeta actual.

```bash
git remote add origin URL
```

🔹 Conecta tu proyecto con GitHub.

```bash
git remote -v
```

🔹 Muestra los repositorios remotos.

---

## 📊 Estado y cambios

```bash
git status
```

🔹 Muestra el estado del proyecto.

```bash
git add archivo.txt
```

🔹 Agrega un archivo al staging.

```bash
git add .
```

🔹 Agrega todos los archivos.

```bash
git diff
```

🔹 Muestra cambios sin guardar.

---

## 💾 Guardar cambios

```bash
git commit -m "mensaje"
```

🔹 Guarda cambios con mensaje.

```bash
git commit -am "mensaje"
```

🔹 Agrega y guarda cambios rápidamente.

```bash
git log
```

🔹 Historial completo de commits.

```bash
git log --oneline
```

🔹 Historial resumido.

---

## 🚀 Subir y traer cambios

```bash
git push origin main
```

🔹 Sube cambios a GitHub.

```bash
git push -u origin main
```

🔹 Primera subida (configura tracking).

```bash
git pull origin main
```

🔹 Trae cambios del repositorio remoto.

```bash
git fetch
```

🔹 Descarga cambios sin aplicarlos.

---

## 🌿 Ramas (Branches)

```bash
git branch
```

🔹 Lista las ramas.

```bash
git branch nueva-rama
```

🔹 Crea una rama.

```bash
git checkout nueva-rama
```

🔹 Cambia de rama.

```bash
git checkout -b nueva-rama
```

🔹 Crea y cambia en un solo paso.

```bash
git merge rama
```

🔹 Fusiona ramas.

```bash
git branch -d rama
```

🔹 Elimina una rama.

---

## 🧹 Correcciones

```bash
git reset archivo.txt
```

🔹 Quita archivos del staging.

```bash
git reset --hard HEAD~1
```

🔹 Vuelve a un commit anterior ⚠️

```bash
git restore archivo.txt
```

🔹 Restaura cambios en un archivo.

```bash
git rm archivo.txt
```

🔹 Elimina archivo del repositorio.

---

## 🔍 Inspección y utilidades

```bash
git show
```

🔹 Muestra detalles de un commit.

```bash
git blame archivo.js
```

🔹 Muestra quién modificó cada línea.

```bash
git stash
```

🔹 Guarda cambios temporales.

```bash
git stash pop
```

🔹 Recupera cambios guardados.

---

## ⭐ Estructura Básica (siempre recordar)

```bash
git add .
git commit -m "Hola Mundo!"
git push origin main
```

---

## 💡 Recordar

Si veo este error:

```bash
error: src refspec main does not match any
```

👉 No olvidar hacer el primer commit:

```bash
git add .
git commit -m "primer commit"
git branch -M main
git push -u origin main
```

---

## ⚠️ No olvidar x2

-  Hacer `pull` antes de empezar a trabajar
-  No usar `--hard` si no estoy segura
