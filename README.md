# Sitio Web Estático en S3 con AWS

Este laboratorio consistió en desplegar un sitio web estático utilizando Amazon S3. El objetivo fue entender cómo funciona el almacenamiento en la nube de AWS y cómo puede configurarse un bucket para alojar archivos HTML públicos de manera segura.

## 🛠️ Qué hice

- Creé un bucket S3 con nombre único.
- Activé la opción de hosting estático.
- Subí los archivos del sitio (HTML, CSS).
- Configuré los permisos públicos del bucket.
- Probé el acceso desde el navegador a la URL generada por AWS.

---

## 🔍 Lo que aprendí

- Cómo gestionar políticas de acceso a nivel de bucket.
- Por qué es importante revisar si un bucket es público y qué implicancias tiene.
- Que aunque el sitio esté accesible, AWS recomienda aplicar medidas adicionales si el contenido es sensible.

---

## 📁 Estructura del proyecto

```plaintext
aws-s3-static-site/
├── web/
│   └── index.html
├── iam/
│   └── policy.json
├── screenshots/
│   └── (capturas del proceso)
└── README.md
```
---

## 🔗 Tecnologías usadas

- AWS S3
- Interfaz web de AWS
- HTML estático

---

## 📸 Capturas del proceso completo

### 1️⃣ Estructura del proyecto creada
![Estructura de carpetas](screenshots/01-crear-carpeta.png)

### 2️⃣ Archivo HTML editado con contenido personalizado
![index.html editado](screenshots/02-index-html.png)

### 3️⃣ Bucket S3 creado desde AWS CLI
![Bucket generado](screenshots/03-crear-bucket.png)

### 4️⃣ Creación del archivo de política IAM
![Crear política](screenshots/04-crear-politica.png)
![Editar archivo policy.json](screenshots/editar_politica.png)

### 5️⃣ Hosting activado y archivo subido correctamente
![Activar hosting](screenshots/05-activar-hosting-subir.png)

### 6️⃣ Verificación del archivo en el bucket S3
![Archivo verificado](screenshots/06-verificar-subida.png)

### 7️⃣ Aplicar política pública al bucket desde terminal
![Aplicar política IAM](screenshots/07-aplicar-politica.png)

### 8️⃣ Confirmación visual: bloqueo público desactivado
![Bloqueo desactivado](screenshots/08-bloqueo-desactivado.png)

### 9️⃣ Edición manual del bloqueo desde consola de AWS
![Editar bloqueo público](screenshots/09-editar-bloqueo.png)

### 🔟 Sitio web funcionando desde URL pública de S3
![Sitio cargado](screenshots/10-sitio-final.png)

---

📫 Contacto: [sebastian.cardenas.t@gmail.com](mailto:sebastian.cardenas.t@gmail.com)


