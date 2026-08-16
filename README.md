# Web Application Design

## Datos del Proyecto

* **Estudiante:** Alexander de la barrera
* **Matrícula:** AL05073920
* **Carrera:** Desarrollo de Software
* **Semestre:** Octavo
* **Materia:** Web Application Design
* **Profesor:** Ricardo González

---

## ¿Para qué sirve Markdown?

**Markdown** nos sirve para escribir y darle formato a un texto de manera rápida, fácil y sin complicaciones. En lugar de estar buscando botones para poner negritas, encabezados o listas como en Word, solo usamos símbolos sencillos 

![Captura de pantalla Markdown](Captura%20de%20pantalla%202026-08-16%20135519.png)

---

## Opciones de Formato / Etiquetado en Markdown

Estas son las principales opciones de etiquetado que utilizo en Markdown para darle formato al texto:

* **Encabezados:** Se usan signos de número `#` al inicio (desde `# Encabezado 1` hasta `###### Encabezado 6`).
* **Texto en Negrita:** Se envuelve el texto con dos asteriscos, por ejemplo: `**texto en negrita**`.
* **Texto en Cursiva:** Se envuelve el texto con un solo asterisco o guion bajo, por ejemplo: `*texto en cursiva*` o `_cursiva_`.
* **Listas Desordenadas:** Se utiliza un asterisco `*`, un guion `-` o un más `+` seguido de un espacio.
* **Listas Ordenadas:** Se utilizan números seguidos de un punto (ej. `1. Primer elemento`, `2. Segundo elemento`).
* **Enlaces (Links):** Se coloca el texto entre corchetes y la URL entre paréntesis: `[Texto del enlace](https://ejemplo.com)`.
* **Imágenes:** Es igual que un enlace pero agregando un signo de exclamación al inicio: `![Texto alternativo](ruta_o_url_de_la_imagen)`.
* **Bloques de Código:** Se encierra el código entre tres comillas invertidas ` ``` ` o se usa una comilla invertida `` `código` `` para código en línea.
* **Citas:** Se coloca el símbolo de mayor que `>` al inicio de la línea.
* **Líneas Divisorias:** Se colocan tres guiones `---` o asteriscos `***` en una línea vacía.

---

## Comandos Principales de Git

Aquí recopilo los comandos de Git que utilizo habitualmente en mi flujo de trabajo:

1. **Revisar el estado del repositorio local:**
   ```bash
   git status
   ```

2. **Agregar archivos (al área de preparación / staging):**
   * *Archivo individual:*
     ```bash
     git add nombre_del_archivo.ext
     ```
   * *Todos los archivos de manera global:*
     ```bash
     git add .
     ```

3. **Agregar comentarios al commit (confirmar cambios):**
   ```bash
   git commit -m "Mensaje descriptivo del commit"
   ```

4. **Subir los cambios al repositorio remoto:**
   ```bash
   git push origin main
   ```

5. **Crear, navegar y eliminar ramas (branches):**
   * *Crear una nueva rama:*
     ```bash
     git branch nombre-de-rama
     ```
   * *Navegar / cambiar a una rama existente:*
     ```bash
     git checkout nombre-de-rama
     ```
   * *Crear y cambiar a una rama al mismo tiempo:*
     ```bash
     git checkout -b nombre-de-rama
     ```
   * *Ver todas las ramas existentes:*
     ```bash
     git branch
     ```
   * *Eliminar una rama:*
     ```bash
     git branch -d nombre-de-rama
     ```

6. **Regresar el repositorio a un commit específico:**
   * *Regresar deshaciendo los commits pero manteniendo los cambios en tus archivos (Soft reset):*
     ```bash
     git reset --soft ID_DEL_COMMIT
     ```
   * *Regresar descartando todos los cambios por completo (Hard reset):*
     ```bash
     git reset --hard ID_DEL_COMMIT
     ```
   * *Revertir un commit creando uno nuevo que deshaga los cambios (Revert seguro):*
     ```bash
     git revert ID_DEL_COMMIT
     ```
