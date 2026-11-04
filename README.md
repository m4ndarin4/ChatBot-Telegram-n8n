# Chatbot de Atención Automatizada con Telegram y n8n

## 📌 Descripción del proyecto

Desarrollo de un chatbot automatizado para la empresa ficticia **Logística & Distribución Andina S.A.C.**, como parte de un proyecto académico de automatización de procesos.

La solución utiliza **Telegram como canal de comunicación, n8n para la automatización de flujos y Google Sheets como fuente de información**, permitiendo responder consultas frecuentes relacionadas con los servicios logísticos y procesos administrativos de la empresa.

El objetivo es facilitar el acceso a la información, reducir la atención manual de consultas repetitivas y demostrar la aplicación de herramientas de automatización en un entorno empresarial simulado.

## 🎯 Objetivos

- Automatizar la atención de consultas frecuentes mediante Telegram.
- Integrar distintas herramientas para gestionar y consultar información.
- Centralizar las respuestas en una base de conocimiento de Google Sheets.
- Implementar un flujo de atención que permita clasificar consultas y generar respuestas.
- Verificar el funcionamiento de la solución mediante pruebas.

## 🛠️ Tecnologías utilizadas

| Herramienta | Aplicación |
|---|---|
| n8n | Desarrollo y automatización del flujo |
| Telegram Bot API | Comunicación con los usuarios |
| Google Sheets | Almacenamiento y consulta de información |
| AI Agent | Procesamiento de consultas y generación de respuestas |
| JSON | Representación y exportación del workflow |

## ⚙️ Funcionalidades principales

- Recepción de mensajes a través de Telegram.
- Identificación y procesamiento de consultas.
- Consulta de una base de conocimiento con preguntas frecuentes.
- Respuestas sobre horarios, ubicación, servicios y procedimientos administrativos.
- Orientación para consultas relacionadas con cotizaciones, pedidos, proveedores y facturación.
- Manejo de consultas sin información disponible.
- Reconocimiento de saludos y mensajes de despedida.

## 🔄 Funcionamiento del sistema

**1. Recepción del mensaje**

El usuario envía una consulta mediante Telegram, que es recibida por el nodo `Telegram Trigger` en n8n.

**2. Procesamiento de la consulta**

El flujo identifica el contenido del mensaje y determina cómo debe procesarse para ofrecer una respuesta adecuada.

**3. Consulta de información**

Se utiliza Google Sheets como base de conocimiento para acceder a la información disponible sobre la empresa.

**4. Generación de respuesta**

El sistema elabora una respuesta en función de la consulta y la información registrada.

**5. Envío del mensaje**

La respuesta se envía automáticamente al usuario mediante Telegram.

## 📸 Evidencias del proyecto

### Flujo de automatización en n8n

![Flujo de automatización](screenshots/flujo-n8n.png)

### Pruebas de funcionamiento en Telegram

![Pruebas del chatbot](screenshots/prueba-telegram.png)

## ✅ Resultados obtenidos

- Implementación funcional de un chatbot integrado con Telegram.
- Integración de Google Sheets como fuente de información.
- Automatización del procesamiento y respuesta de consultas frecuentes.
- Validación del funcionamiento mediante pruebas de interacción.
- Desarrollo de un flujo que permite actualizar la información consultada desde Google Sheets.

## 👩‍💻 Mi participación

Responsable de la implementación completa del chatbot, incluyendo:

- Diseño y configuración del workflow en n8n.
- Creación y conexión del bot de Telegram.
- Integración con Google Sheets.
- Configuración del procesamiento de consultas y respuestas.
- Ejecución de pruebas funcionales.
- Identificación y corrección de errores durante la implementación.
- Documentación del funcionamiento de la solución.

## 📂 Archivos del proyecto

El repositorio contiene el workflow exportado de n8n en formato JSON, documentación del proyecto y evidencias visuales de su funcionamiento.

## 📚 Contexto

Proyecto desarrollado con fines académicos para aplicar conceptos de automatización de procesos, integración de aplicaciones y gestión de información mediante herramientas digitales.
