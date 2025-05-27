# INFORME TÉCNICO PREVENTIVO

## Observación sobre un posible subdominio inactivo asociado a un dominio público

---
Fecha: 26/05/2025
Remitente: Favio Joel Zalazar
Destinatario: Área Técnica – Entidad Pública Nacional
---

## Introducción

El presente informe tiene como finalidad comunicar, de forma preventiva y con intención colaborativa, una observación técnica vinculada a un subdominio aparentemente inactivo perteneciente a un dominio de carácter público. El análisis fue realizado utilizando herramientas de acceso libre y sin ejecutar acciones invasivas, priorizando el respeto a la infraestructura digital y a las normativas vigentes.

## Metodología del Análisis

Para realizar la observación se emplearon exclusivamente herramientas pasivas de análisis OSINT (Open Source Intelligence), entre ellas

    Criminal IP: Plataforma de inteligencia de amenazas que permite consultar información histórica de dominios y subdominios

    nslookup y dig: Herramientas estándar de consulta DNS

Estas herramientas se utilizaron únicamente para verificar información públicamente disponible, sin realizar ningún tipo de escaneo activo, interacción directa con servidores ni acciones que pudieran considerarse intrusivas

## Descripción Técnica

    Subdominio observado: Un subdominio bajo un dominio de nivel gubernamental nacional

    Estado actual: No responde a consultas DNS estándar (NXDOMAIN o sin respuesta)

    Historial técnico: En consultas realizadas a través de Criminal IP, se observó que el subdominio estuvo previamente configurado con un certificado digital inválido o mal gestionado

## Riesgos Potenciales

    Percepción pública de inseguridad: Subdominios inactivos o mal configurados pueden generar confusión o dar una impresión negativa sobre la infraestructura tecnológica.

    Riesgo de apropiación por terceros (subdomain takeover): Si el subdominio no está vinculado actualmente a un recurso activo y no se ha eliminado correctamente, podría ser reutilizado maliciosamente.

    Persistencia en buscadores y plataformas OSINT: Aun estando inactivo, el subdominio puede seguir apareciendo en motores de búsqueda y herramientas automatizadas, perpetuando su visibilidad.

## Recomendaciones Técnicas

    Auditoría interna del subdominio: Verificar si su desactivación fue intencional y si continúa siendo necesario

    Revisión de registros DNS: Confirmar que el subdominio no esté expuesto a apropiación externa y aplicar medidas preventivas

    Redirección o aclaración pública: En caso de que haya enlaces públicos aún vigentes, se sugiere redirigir o dejar un mensaje informativo

    Monitoreo más amplio: Considerar una revisión periódica de todos los subdominios asociados al dominio principal, en busca de casos similares

## Cierre

Este informe es compartido con el único fin de colaborar proactivamente en la mejora continua de la seguridad y percepción pública de los activos digitales asociados a instituciones del Estado Argentino
