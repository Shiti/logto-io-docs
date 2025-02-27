---
sidebar_position: 4
---

# Códigos de respaldo

## Conceptos {#concepts}

Los códigos de respaldo, también conocidos como código de recuperación, son un código de un solo uso para la autenticación multifactor (MFA), actuando como respaldo en caso de que los factores de autenticación primarios del usuario (por ejemplo, la aplicación de autenticación o el token de hardware) no estén disponibles.

Perderlos puede llevar a desafíos en la recuperación de la cuenta. Por lo tanto, se recomienda configurar un factor primario adicional antes de habilitar los códigos de respaldo, dándole prioridad.

Logto genera automáticamente 10 códigos de respaldo para los usuarios una vez que configuran un factor adicional. Cada código es de un solo uso. Se aconseja a los usuarios regenerar un nuevo conjunto de códigos en la Configuración de la Cuenta de Usuario (accesible a través de la [Management API](/integrate-logto/interact-with-management-api/)) antes de usar todos los códigos existentes.

## Flujos de autenticación {#authentication-flows}

- **Flujos de configuración de códigos de respaldo**

![Flujo de configuración de códigos de respaldo](./assets/backup-codes-set-up-flow.png)

- **Flujo de verificación de códigos de respaldo**

![Flujo de verificación de códigos de respaldo](./assets/backup-codes-verification-flow.png)
