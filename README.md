# 🌍 Sistema de Registro de Puntos de Interés

Aplicación web para registrar, gestionar y consultar puntos de interés geolocalizados mediante una API REST y una base de datos geoespacial.

---

## 🚀 Características

- Registro de puntos con coordenadas geográficas
- Filtrado por categoría
- Búsqueda por proximidad (radio en metros)
- API REST con documentación automática
- Arquitectura contenerizada con Docker
- Persistencia de datos

---

## 🛠️ Tecnologías

- FastAPI
- PostgreSQL + PostGIS
- Nginx
- Docker Compose

---

## 🧱 Arquitectura

El sistema está compuesto por tres servicios:

- **db:** base de datos geoespacial
- **app:** API REST
- **proxy:** servidor Nginx (punto de entrada)

---

## ⚙️ Configuración

Crear un archivo `.env` en la raíz del proyecto:

```env
POSTGRES_USER=usuario
POSTGRES_PASSWORD=contraseña
POSTGRES_DB=nombre_db


## ⚙️ Ejecucion
docker compose up --build
docker compose up

🌐 Acceso
Aplicación: http://localhost:81