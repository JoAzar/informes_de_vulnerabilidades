# Informe de Vulnerabilidad Crítica – Sunsight Solutions

**Fecha del hallazgo:** 4 de Junio del 2025

**Reportado por:** Red

**Severidad:** Crítica 
 
**Estado:** Divulgación responsable en proceso

---

## 🛡️ Descripción general

Este informe documenta una **vulnerabilidad crítica** detectada en un recurso público perteneciente a **Sunsight Solutions**, una empresa que, según información pública, ofrece soluciones tecnológicas posiblemente utilizadas por el **Ejército de los Estados Unidos**

---

## 🔍 Detalles de la vulnerabilidad

- **Tipo de vulnerabilidad:** Exposición de credenciales en texto plano

- **Recurso afectado:** Archivo accesible públicamente mediante una URL con el siguiente formato:

https://[no_publicado_por_confidencialidad]/archivo.txt

- **Contenido del archivo:**  
El archivo `.txt` contiene **credenciales de acceso** (usuario y contraseña) en **texto plano**, sin ningún tipo de cifrado o restricción de acceso

---

## ⚠️ Riesgos potenciales

- Acceso no autorizado a sistemas internos

- Compromiso de servicios críticos

- Pérdida o filtración de información confidencial

- Riesgo elevado debido a la posible relación con entidades gubernamentales o militares

---

## ✅ Recomendaciones

1. **Eliminar inmediatamente** el archivo expuesto o protegerlo con mecanismos de autenticación

2. **Cambiar todas las credenciales** que hayan sido expuestas

3. Realizar una auditoría completa del sistema para identificar accesos no autorizados

4. Implementar políticas de gestión segura de contraseñas y archivos sensibles

5. Establecer un protocolo de divulgación responsable para este tipo de incidentes

---

## 📩 Estado de la divulgación

Se ha intentado una **comunicación responsable** con la empresa para notificar esta vulnerabilidad. Se recomienda al equipo de seguridad de Sunsight tomar acción de forma inmediata.

---

## Evidencia

Se adjunta una imagen que muestra el acceso directo al archivo vulnerable y parte del contenido sensible (redactado parcialmente para preservar la confidencialidad).

---

## Nota final

Este informe fue redactado con fines **responsables y éticos**, buscando mejorar la seguridad del ecosistema digital. No se ha explotado ni difundido la información sensible

---

Creado por Favio Joel Zalazar