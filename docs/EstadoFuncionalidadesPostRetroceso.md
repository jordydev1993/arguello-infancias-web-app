# Estado de funcionalidades después del retroceso

**Proyecto:** Argüello Infancias

**Versión de referencia:** `99752ec`

## 1. Integración con Didit

**Estado: Parcialmente implementado.**

En la versión de referencia existe un endpoint para recibir webhooks de Didit. Su implementación se limita a validar la firma y el formato de los eventos recibidos. No se encuentra operativo el proceso completo de verificación de identidad y autorización de retiro.

**Pendiente:**
- Crear las tablas `sesiones_didit` y `retiros`.
- Guardar los resultados de verificación en la base de datos.
- Actualizar los estados de las sesiones de verificación.
- Validar las autorizaciones vigentes para retirar NNyA.
- Completar el flujo de verificación de identidad y retiro.

## 2. Reportes SENAF

**Estado: Pendiente de implementación en la versión actual.**

**Funcionalidades pendientes:**
- Gestión de reportes SENAF.
- Formularios de creación y edición.
- Generación de informes PDF.
- Redacción de informes.
- Consulta y visualización de reportes.

## 3. Observaciones

Las funcionalidades pendientes deberán revisarse, integrarse y validarse antes de considerarse disponibles en el sistema.

Los desarrollos posteriores al commit de referencia se conservan en la rama `version-con-ia`.

Este documento refleja el estado funcional de la versión de referencia.