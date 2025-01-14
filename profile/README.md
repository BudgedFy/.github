# BudgedFy : Chatbot para Registro de Gastos con IA

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de un chatbot impulsado por IA que permite a los usuarios registrar y gestionar sus gastos en Google Sheets. Además, ofrece funcionalidades avanzadas, como notificaciones y suscripciones para diferentes niveles de acceso y beneficios.

---

## Funcionalidades Clave

### Registro de Gastos

- El chatbot permite a los usuarios registrar sus gastos de forma rápida y eficiente en Google Sheets.

### Gestión de Límites

- **Aviso de Mantenimiento**: Si el usuario supera su límite diario, el sistema muestra un aviso para alertar sobre la situación.

### Notificaciones

- **Suscripciones**: El chatbot envía un aviso de "warning" cuando quedan 3 días para que la suscripción expire. También envía recordatorios 2 días después de la expiración.
- **Promociones**: Un sistema cron envía mensajes a los usuarios que solo compraron la plantilla, ofreciendo la suscripción al servicio completo.

### Opciones de Suscripción

- **Con IA**: Acceso completo con funcionalidades avanzadas.
- **Sin IA**: Flujo lineal con validaciones mínimas.

### Futuras Versiones

- **V2**: Implementar una página de catálogo (sin pasarela de pagos).
- **V3**: Añadir pasarela de pagos.
- **V4**: Desarrollo de aplicación móvil.
- **V5**: Captura automática de gastos a partir de notificaciones (correos, mensajes, Google Pay, Apple Pay, apps de dinero, etc.).

---

## Estructura de Precios

| Plan        | Precio | Tokens Incluidos |
| ----------- | ------ | ---------------- |
| **1 mes**   | 9.9k   | 25,000 tokens    |
| **3 meses** | 27.9k  | 75,000 tokens    |
| **6 meses** | 47.9k  | 150,000 tokens   |
| **1 año**   | 94.9k  | 300,000 tokens   |

---

## Tecnologías Utilizadas

- **Google Sheets API**: Para el almacenamiento y gestión de datos.
- **Procesamiento de Lenguaje Natural (NLP)**: Para entender las solicitudes del usuario.
- **Node.js o Python**: Para el backend del chatbot.
- **Cron Jobs**: Para enviar notificaciones y promociones programadas.
- **Frameworks de Desarrollo Móvil** (en futuras versiones): Para la creación de aplicaciones móviles.

---
