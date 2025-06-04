# Informe de Vulnerabilidad Crítica – Khoury College of Computer Sciences

**Fecha del hallazgo:** 04 de Junio del 2025

**Reportado por:** Red

**Severidad:** 🚨 Crítica

**Estado:** Divulgación responsable en proceso

---

## 🏛️ Sobre Khoury College

El **Khoury College of Computer Sciences** es la facultad de ciencias de la computación de la Universidad de Northeastern, ubicada en Boston, Massachusetts, Estados Unidos.

Fundada en 1982, fue la primera facultad en EE. UU. dedicada exclusivamente a la informática. 

La institución ofrece programas de grado y posgrado en ciencias de la computación, ciencia de datos y ciberseguridad, y mantiene una fuerte orientación hacia la investigación aplicada en áreas como la ciberseguridad, la informática en salud y la ciencia de redes y datos

---

## Detalles de la vulnerabilidad

- **Tipo de vulnerabilidad:** Exposición de credenciales en texto plano

- **Recurso afectado:** Archivo accesible públicamente mediante una URL con el siguiente formato:

https://[dominio_afectado_confidencial]/archivo.txt


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

Se ha intentado una **comunicación responsable** con la institución para notificar esta vulnerabilidad

Se recomienda al equipo de seguridad de Khoury College tomar acción de forma inmediata

---

## 📎 Evidencia

Se adjunta una imagen que muestra el acceso directo al archivo vulnerable y parte del contenido sensible (redactado parcialmente para preservar la confidencialidad y seguridad)

---

## 📘 Nota final

Este informe fue redactado con fines **responsables y éticos**, buscando mejorar la seguridad del ecosistema digital

No se ha explotado ni difundido la información sensible

---

Creado por Favio Joel Zalazar
