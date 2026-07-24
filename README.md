# Ingeniería de Software II  

# RehabilitAR  
Proyecto web  
**[Ver aplicacion en vivo](rehabilitación-ar.vercel.app)**

---

## Descripción

Este repositorio contiene el desarrollo práctico de la materia **Ingeniería de Software II**, centrada en el ciclo de vida completo del software.

El proyecto desarrollado durante la cursada consiste en la construcción de un sistema web para un centro de rehabilitación llamado **RehabilitAR**, con el objetivo de digitalizar y optimizar la gestión de clientes, clases, pagos y administración general.

---

## Proyecto: RehabilitAR

**RehabilitAR** es una plataforma web orientada a la gestión integral de un centro de rehabilitación.

### Objetivo

Mejorar la eficiencia operativa del centro mediante la automatización de:

* Gestión de clientes (abonados y no abonados)
* Administración de clases y turnos
* Control de asistencia mediante QR
* Manejo de pagos y suscripciones
* Gestión de listas de espera
* Generación de reportes y estadísticas

---

## Funcionalidades principales

### Clientes

* Registro y gestión de cuenta
* Suscripción mensual (clase semanal)
* Reserva de clases individuales
* Cancelación de turnos
* Obtención de créditos por cancelaciones anticipadas
* Registro de asistencia mediante QR
* Recepción de notificaciones

### Profesores

* Visualización de clases asignadas
* Registro y validación de asistencia
* Gestión de comentarios por clase
* Asignación a clases disponibles

### Administradores

* Creación, edición y eliminación de clases
* Gestión de usuarios y roles
* Control de pagos
* Gestión de listas de espera
* Generación de reportes y estadísticas
* Administración de suspensiones

### Recepcionistas

* Registro de clientes
* Gestión de pagos presenciales
* Asistencia operativa

---

## Reglas de negocio destacadas

* Suscripciones mensuales con descuentos si se contratan a mitad de mes
* Suspensión automática por:
  * Falta de pago
  * Inasistencias (>50%)
* Créditos por cancelaciones con 48 hs de anticipación
* Límite de 3 créditos por cliente
* Clases canceladas si:
  * No hay profesor asignado (12h antes)
  * No se alcanza el 50% de ocupación
* Listas de espera con prioridad para abonados
* Registro de asistencia mediante código QR

---

## Contenidos de la materia

* Gestión de proyectos
* Diseño de software
* Implementación
* Verificación y validación
* Mantenimiento
* Auditoría y peritaje

---

## Metodología de trabajo

* Trabajo en equipos de 5 integrantes
* Uso de metodologías ágiles (Scrum)
* Seguimiento mediante entregas y demos

---

## Cronograma práctico

### Entregas iniciales

* **Entrega 1**

  * Entrevista
  * Cuestionario
  * Épicas

* **Entrega 2**

  * SRS+PGP
  * Pila de producto
  * Historias de Usuario

---

### Iteraciones (Scrum)

* Planning 1

* Scrum Diario

* Pre-demo

* Demo 1

* Planning 2

* Scrum Diario

* Pre-demo

* Demo 2

---

## Repositorios del codigo fuente

* **Frontend:** [Repo de frontend en Github](https://github.com/Dulceguez/RehabilitAR/tree/main/frontend)
* **Backend:** [Repo de backend en Github](https://github.com/Dulceguez/RehabilitAR/tree/main/backend)
  
---

## Tecnologías e integraciones

* API de pagos (Mercado Pago)
* Sistema de notificaciones por email (SMTP)
* API de feriados
* Validación de documentos mediante IA
* Código QR para asistencia

---

## Equipo

Proyecto desarrollado en el marco de la materia Ingeniería de Software II.
Trabajo grupal con roles definidos y evaluaciones individuales y grupales.

---

## Notas

* El sistema está diseñado como una solución web responsive (PC y mobile)
* Se prioriza la usabilidad, especialmente para usuarios adultos mayores
* Se contemplan futuras mejoras como:
  * Nuevos métodos de pago
  * Mejores reportes
  * Gestión avanzada de apto físico
