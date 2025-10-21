
# 🧠 Guía básica de Git y GitHub

Este documento explica de forma simple los **comandos principales de Git** y el **proceso paso a paso** para subir tus cambios a un repositorio en **GitHub**.

---

## 🚀 Principales comandos de Git

### 1. `git init`
Sirve para **iniciar un nuevo repositorio** en la carpeta donde estás trabajando.  
Después de usarlo, Git empezará a llevar el control de los cambios de tus archivos.  
```bash
git init
````

---

### 2. `git add`

Agrega los archivos que cambiaste al "área de preparación" (staging area), es decir, los deja listos para hacer un **commit**.

```bash
git add archivo_a_enviar
```

O si quieres agregar todos los archivos modificados:

```bash
git add .
```

---

### 3. `git commit`

Guarda los cambios en el repositorio junto con un mensaje que explica qué hiciste.

```bash
git commit -m "Agregué el archivo principal del proyecto"
```

---

### 4. `git status`

Muestra el estado actual del repositorio: qué archivos están modificados, listos para guardar o sin seguimiento.

```bash
git status
```

---

### 5. `git log`

Muestra el historial de los commits que has hecho, con su autor, fecha y mensaje.

```bash
git log
```

---

### 6. `git branch`

Muestra o crea ramas (branches) del proyecto.

* Ver las ramas:

  ```bash
  git branch
  ```
* Crear una nueva rama:

  ```bash
  git branch nueva-rama
  ```

---

### 7. `git checkout`

Sirve para **cambiar de rama** o **volver a un commit anterior**.

```bash
git checkout main
```

---

### 8. `git push`

Envía los cambios que hiciste en tu computadora al repositorio de **GitHub**.

```bash
git push origin main
```

---

### 9. `git pull`

Descarga los cambios más recientes del repositorio remoto (GitHub) a tu computadora.

```bash
git pull origin main
```

---

### 10. `git clone`

Copia (descarga) un repositorio completo desde GitHub a tu computador.

```bash
git clone https://github.com/usuario/nombre-del-repo.git
```

---

## 💻 Pasos para enviar tus cambios a GitHub

1. **Crea un repositorio en GitHub.**
   Entra a tu cuenta → botón **New Repository** → ponle un nombre → crea el repositorio.

2. **Abre tu proyecto en tu computador.**
   Si no es un repositorio todavía, ejecútalo:

   ```bash
   git init
   ```

3. **Conecta tu proyecto local con GitHub.**
   Copia la URL de tu repositorio (por ejemplo: `https://github.com/usuario/proyecto.git`) y ejecútalo:

   ```bash
   git remote add origin https://github.com/usuario/proyecto.git
   ```

4. **Agrega tus archivos al área de preparación.**

   ```bash
   git add .
   ```

5. **Crea un commit con un mensaje.**

   ```bash
   git commit -m "Primer commit del proyecto"
   ```

6. **Envía los cambios a GitHub.**

   ```bash
   git push -u origin main
   ```

7. **Verifica en GitHub.**
   Refresca la página del repositorio y verás tus archivos en línea.

---

## ✅ Consejo final

Git puede parecer complicado al inicio, pero con práctica se vuelve una herramienta muy poderosa.
Lo importante es **entender qué hace cada comando** antes de usarlo.

```

---

