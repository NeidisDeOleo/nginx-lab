# 🐳 Práctica: Servidor Web Nginx con Docker Compose

## 📌 Descripción

En esta práctica se implementa un servidor web utilizando Nginx dentro de un contenedor Docker, gestionado con Docker Compose.
El objetivo es servir una página HTML básica desde un entorno local.

---

## 🎯 Objetivos

* Crear un contenedor Nginx con Docker Compose
* Montar un volumen para servir archivos HTML
* Verificar el funcionamiento del servidor en el navegador
* Subir el proyecto a GitHub

---

## 📁 Estructura del proyecto

nginx-lab/
│── docker-compose.yml
│── src/
│   └── index.html

---

## ⚙️ Tecnologías utilizadas

* Docker
* Docker Compose
* Nginx
* HTML

---

## 🚀 Pasos para ejecutar el proyecto

1. Clonar el repositorio:

```
git clone https://github.com/TU-USUARIO/nginx-lab.git
```

2. Entrar al directorio:

```
cd nginx-lab
```

3. Ejecutar el contenedor:

```
docker compose up -d
```

4. Abrir en el navegador:

```
http://localhost:8080
```

---

## ✅ Resultado esperado

Se mostrará una página con el mensaje:

Hola Mundo desde Docker 🚀

---

## 📸 Evidencias

(Inserte aquí capturas de pantalla del proyecto funcionando)

