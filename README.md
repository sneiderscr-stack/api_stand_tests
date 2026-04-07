# API Stand Tests

Este proyecto contiene pruebas automatizadas para la API de creación de usuarios.

## 📌 Descripción

Se validan diferentes escenarios para el campo `firstName`, incluyendo:

- Longitud mínima y máxima
- Caracteres válidos e inválidos
- Tipos de datos incorrectos
- Campos obligatorios

## 🛠 Tecnologías utilizadas

- Python
- Pytest
- Requests

## 📂 Estructura del proyecto

- `configuration.py` → configuración de la API
- `data.py` → datos de prueba
- `sender_stand_request.py` → envío de solicitudes
- `create_user_test.py` → pruebas automatizadas

## ▶️ Cómo ejecutar las pruebas

```bash
pytest

## 👤 Autor

Sneider Corredor