# 🤖 Sistema de Detección de Quejas y Respuesta Automática para E-commerce

Proyecto final de la materia **Procesamiento del Habla**, cuyo objetivo es desarrollar un prototipo capaz de detectar quejas en mensajes de clientes y generar respuestas automáticas. Simula el funcionamiento de un sistema de soporte al cliente para empresas de e-commerce.

---

## 🎯 Objetivo

Automatizar el proceso de atención al cliente mediante un sistema que:

- Detecta si un ticket contiene una queja.
- Clasifica el tipo de problema.
- Extrae información clave del mensaje.
- Genera una respuesta automática personalizada.

---

## 🛠️ Tecnologías y Herramientas

- [Pandas](https://pandas.pydata.org/) para manipulación de datos.
- [Transformers](https://huggingface.co/transformers/) y Pipelines de Hugging Face para clasificación y análisis de texto.
- [Gemini API](https://ai.google.dev/) de Google AI para generación de texto (requiere credenciales).
- [Gradio](https://www.gradio.app/) para la creación de una interfaz de prueba.
- Python y Jupyter Notebook para desarrollo y documentación.

---

## ⚙️ Funcionamiento del Sistema

1. **Simulación de datos**  
   Se genera un conjunto de tickets ficticios con diferentes categorías: quejas, consultas y comentarios neutros.

2. **Clasificación de quejas**  
   Se emplea un modelo de lenguaje basado en Transformers para identificar si el mensaje contiene una queja.

3. **Extracción del tema principal**  
   Se analiza el texto para detectar el problema principal (ej.: entrega, producto, atención, etc.).

4. **Generación de respuesta automática**  
   Se genera una respuesta basada en el contenido del mensaje, usando la API de Gemini o un modelo local.

5. **Interfaz gráfica (demo)**  
   Implementación de una demo interactiva con Gradio que permite ingresar un mensaje y recibir una respuesta automática.

---

## 📚 Créditos

Desarrollado por:

- Maria Florencia Lopez  
- Daiana Elizabeth Gomez  
- Jordi Galman  

Como parte del trabajo final para la materia **Procesamiento del Habla**.

---

## 📌 Notas

- Este sistema es un **prototipo** con fines académicos y no reemplaza soluciones profesionales de atención al cliente.
- Si no contás con acceso a la API de Gemini, podés reemplazarla por un modelo local de Hugging Face.
