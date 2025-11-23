# 📘 Tarea 4 – Almacenamiento y Consultas de Datos en Big Data  
### 🗄️ Implementación de Base de Datos NoSQL en MongoDB

Este repositorio contiene el desarrollo completo de la **Fase 1 y Fase 2 de la Tarea 4** del curso *Almacenamiento y Consultas de Datos en Big Data*, utilizando **MongoDB Compass** como herramienta principal.

---

## 📂 Contenido del repositorio

- `/dataset/`  
  Contiene los archivos JSON utilizados para importar en MongoDB Compass:
  - `usuarios_compass.json`
  - `publicaciones_compass.json`
  - `comentarios_compass.json`

- `/consultas/`  
  Incluye los scripts de las consultas realizadas durante la Fase 2:
  - Consultas básicas
  - Consultas con filtros y operadores
  - Consultas de actualización
  - Eliminación de documentos
  - Agregaciones

- `/documentacion/`  
  Incluye el ensayo de la Fase 1 en formato PDF y las explicaciones de las consultas.

---

## 🧩 Fase 1: Ensayo — Comparación de Bases de Datos NoSQL

Se realizó un ensayo académico en el que se comparan los cuatro principales tipos de bases de datos NoSQL:

- Clave–Valor  
- Documentos  
- Columnas  
- Grafos  

Incluye ventajas, desventajas y casos de uso típicos.  
El ensayo está disponible en `/documentacion/`.

---

## 🧪 Fase 2: Implementación en MongoDB

Para esta fase se utilizó **MongoDB Compass** con tres colecciones principales:

- `usuarios`
- `publicaciones`
- `comentarios`

### ✔ 1. Inserción de documentos  
Los documentos fueron insertados mediante la opción **Insert Document**, utilizando JSON puro.  
Ejemplo:

```json
{
  "id": "usuario101",
  "nombre": "Nuevo Usuario",
  "email": "nuevo@example.com",
  "fecha_registro": "2024-04-01",
  "rol": "usuario",
  "intereses": ["salud", "tecnologia"],
  "estado": "activo"
}
