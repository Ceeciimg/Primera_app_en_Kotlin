# 📱 Primera App en Kotlin con Jetpack Compose

**Nombre:** Cecilia Molina García  
**Asignatura:** Programación multimedia y dispositivos móviles  

---

## 📖 Explicación del código

### 1. Estructura principal del proyecto
- Se define la clase principal **MainActivity**, que hereda de `ComponentActivity`.  
- Dentro del método `onCreate`, se usa `setContent` para indicar que la interfaz de usuario se construirá con **Jetpack Compose**.  
- Se aplica el tema de la app y se llama a la función **HelloApp()**, que contiene toda la lógica visual.  

---

### 2. Declaración de estados
- **name** → almacena el texto que el usuario escribe.  
- **showGreeting** → controla si se muestra la pantalla de saludo o la pantalla inicial.  

---

### 3. Diseño de la pantalla principal
- Se muestra el texto: **"¿Cómo te llamas?"**  
- Un campo de texto `TextField` permite al usuario escribir su nombre.  
- Un botón `Button` cambia el valor de `showGreeting` a `true` si el campo no está vacío.  

---

### 4. Diseño de la pantalla de saludo
- Se muestra un saludo personalizado utilizando el nombre introducido por el usuario.  
- El botón **"Volver"** cambia `showGreeting` a `false`, lo que hace que Compose reconstruya la interfaz y regrese a la pantalla inicial.  

---

## 🎯 Resultado
La aplicación tiene dos “pantallas” dentro de una sola actividad, gestionadas mediante estados:  
1. Pantalla inicial con campo de texto y botón.  
2. Pantalla de saludo personalizada con opción de volver.  

---

## 🚀 Tecnologías utilizadas
- **Kotlin**  
- **Jetpack Compose**  

---

## 📌 Notas
Este proyecto es un ejemplo introductorio para comprender cómo manejar **estados** y **navegación básica** en Jetpack Compose.
