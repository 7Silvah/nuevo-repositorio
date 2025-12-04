# Resumen del Primer Commit en GitHub

## Paso a Paso

### 1. Análisis del Repositorio Clonado
- Se analizó la estructura del repositorio clonado, que contenía los siguientes archivos:
  - `LICENSE`
  - `README.md`

### 2. Creación de Archivo de Prueba
- Se creó un archivo llamado [`prueba.txt`](prueba.txt:1) con el siguiente contenido:
  ```plaintext
  Este es un archivo de prueba para el primer commit.
  ```

### 3. Primer Commit Local
- Se ejecutaron los siguientes comandos para realizar el primer commit local:
  ```bash
  git add prueba.txt
  git commit -m "Primer commit: archivo de prueba añadido"
  ```
- El commit se realizó exitosamente con el hash `b7a1ecb`.

### 4. Subida del Commit a GitHub
- Se ejecutó el siguiente comando para subir el commit a GitHub:
  ```bash
  git push origin main
  ```
- El commit se subió exitosamente al repositorio remoto.

### 5. Verificación del Commit
- El commit se puede verificar en el repositorio de GitHub: [https://github.com/7Silvah/nuevo-repositorio/commit/b7a1ecb](https://github.com/7Silvah/nuevo-repositorio/commit/b7a1ecb)