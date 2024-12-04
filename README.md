# Clima_Alexa
<br>
<h1 align="center"> Universidad Tecnológica de Xicotepec de Juárez </h1>
<br>

<h2 align="center"> Desarrollo Móvil Integral </h2>
<h2 align="center"> José Zahid Ramirez Estudillo </h2>

<h2> Objetivo </h2>
Configurar y desarrollar habilidades personalizadas para dispositivos habilitados con Alexa, con el propósito de comprender y aplicar el manejo de mensajes personalizados mediante las herramientas y servicios de Amazon Developer.

--- 
<h2 align="center"> Documentación de la práctica</h2>

## Estructura de las carpetas 
<p align="center">
  <img src="/img/estructura-carpetas.png" alt="Estructura de carpetas" width="600"/>
</p>

---

## Pasos para Crear la Skill

### 1. Crear una cuenta en Amazon Developer
- Accede a [Amazon Developer Console](https://developer.amazon.com/).
- Crea una cuenta o inicia sesión.
- Acepta los términos y condiciones para activar las herramientas de desarrollo.

---

### 2. Crear la Skill
- En la consola de Alexa, selecciona **"Create Skill"**.
- Asigna el nombre `Utxj-Clima`.
- Selecciona el idioma español [ES].
- Elige la plantilla **"Custom"** y selecciona **"Start from Scratch"**.

<p align="center">
  <img src="/img/create-skill.png" alt="Crear Skill en Alexa" width="600"/>
</p>

---

### 3. Diseñar el Modelo de Interacción
1. Ve a la pestaña **"Interaction Model"** y selecciona **"Intents"**.
2. Crea un nuevo intent llamado `Clima` con las siguientes frases de ejemplo:
   - "como estara el clima"
   - "va hacer calor"
   - "me llevo sueter"
   - "Hara sol hoy"
   - "Dame el clima"
3. Guarda los cambios y construye el modelo haciendo clic en **"Build Model"**.

<p align="center">
  <img src="/img/interaction-model.png" alt="Modelo de interacción" width="600"/>
</p>

---

### 4. Configurar el Backend
1. Importamos el archivo de código previamente proporcionado que incluye:
   - Lógica para manejar el intent `Clima`.
   - Integración con la API de OpenWeatherMap.
   - Respuestas dinámicas para el usuario.
2. Configura los permisos necesarios para la ejecución de la skill.

<p align="center">
  <img src="/img/lambda-configuration.png" alt="Configuración de Lambda" width="600"/>
</p>

---

### 5. Probar la Skill
1. Activa el modo de prueba en la pestaña **"Test"**.
2. Realiza pruebas con comandos como:
   - "Alexa, abre clima zahid."
   - "como estara el clima"
   - "va hacer calor"
   - "me llevo sueter"
   - "Hara sol hoy"
   - "Dame el clima"

<p align="center">
  <img src="/img/test-skill.png" alt="Pruebas de la Skill" width="600"/>
</p>

---

## Requisitos
- Cuenta de Amazon Developer.
- API Key de OpenWeatherMap.

