# Android Skills Portfolio

**Número de equipo:** 3  
**Integrantes:**
- Ángel Ortiz - Desarrollador principal y diseñador UI
- Karen López - Tester y apoyo en diseño
- Roberto Sánchez - Documentación y control de versiones

## ¿Qué hace la aplicación?

La aplicación **Android Skills Portfolio** permite a los usuarios practicar y reforzar sus conocimientos de Android Studio a través de una interfaz sencilla. Cuenta con un sistema de login funcional y navegación entre pantallas que muestran ejercicios prácticos como uso de `EditText`, `Button`, validación de datos y navegación con `Intent`.

## Tipo de sistema

**Proyecto Móvil Java** desarrollado en Android Studio.

## Librería externa implementada

- **Glide**: para cargar imágenes desde recursos o URLs de forma eficiente.
  
---

## Ejercicios incluidos

### 🧪 Ejercicio 1: Pantalla de Login
**Captura de pantalla:**  
![Login](./screenshots/login.png)  
**Descripción:**  
Pantalla de inicio donde el usuario debe ingresar un correo y contraseña. Solo se permite el acceso con una combinación válida.

### 🧪 Ejercicio 2: Navegación entre actividades  
**Captura de pantalla:**  
![Navegación](./screenshots/navegacion.png)  
**Descripción:**  
Después del login, el usuario puede acceder a distintos ejercicios usando botones que navegan entre actividades usando `Intent`.

### 🧪 Ejercicio 3: Validación de campos  
**Captura de pantalla:**  
![Validación](./screenshots/validacion.png)  
**Descripción:**  
Campos que muestran mensajes si están vacíos o si la entrada no cumple con los requisitos básicos.

---

## Requisitos Técnicos

- **Mínimo SDK:** API 24 (Android 7.0 Nougat)
- **Target SDK:** API 34 (Android 14)
- **Librerías externas utilizadas:**
  - `implementation 'com.github.bumptech.glide:glide:4.16.0'`

**Buenas prácticas aplicadas:**
- Uso de nombres de variables descriptivos.
- Separación de lógica en métodos.
- Comentarios claros y precisos en las secciones importantes del código.

---

## Pasos para instalar y ejecutar el proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/android-skills-portfolio.git
