# Planificación Scrum — Argüello Infancias — Sistema de gestión de residencia NNyA (web + mobile)

> Estado al 29/10/2026. Planificación con tiempos realistas para un equipo de cuatro estudiantes de 3er año de Analista de Sistemas. El detalle editable está en el Excel `Planificacion-Sprints-Gantt.xlsx`.

## Supuestos

| Concepto | Valor |
|---|---|
| Inicio | 12/03/2026 |
| Metodología | Scrum, sprints de 2 semanas |
| Dedicación | 12 h/semana por integrante |
| Ceremonias | 4 h/persona/sprint (planning, dailies asincrónicas, review y retro) |
| Capacidad por persona | 20 h de tareas por sprint · 14 h en sprints con parciales o finales |
| Receso | Receso invernal (sin sprint): 02/07/2026 – 15/07/2026 |

## Equipo

| Integrante | Rol | Horas de tareas | Horas totales (con ceremonias) |
|---|---|---:|---:|
| **Jordy** | Líder de proyecto / Scrum Master · Backend y base de datos (Supabase, RLS) | 344 | 420 |
| **Meli** | QA y testing · Integraciones (Didit) | 344 | 420 |
| **Cami** | Frontend y UX · Innovaciones de interfaz | 344 | 420 |
| **Sofi** | Análisis funcional, specs y documentación · Desarrollo mobile | 344 | 420 |
| **Total** | | **1376** | **1680** |

## Resumen de sprints

| Sprint | Fechas | Objetivo | Capacidad | Horas | Estado |
|---|---|---|---|---:|---|
| 0 | 12/03/2026 – 25/03/2026 | Inicio del proyecto y relevamiento inicial | normal | 80 | ✅ Completado |
| 1 | 26/03/2026 – 08/04/2026 | Procesos del negocio | normal | 80 | ✅ Completado |
| 2 | 09/04/2026 – 22/04/2026 | Requerimientos y modelo de datos | normal | 80 | ✅ Completado |
| 3 | 23/04/2026 – 06/05/2026 | Arquitectura y especificación funcional | reducida (Parciales 1er cuatrimestre) | 56 | ✅ Completado |
| 4 | 07/05/2026 – 20/05/2026 | Setup técnico y sistema de diseño | normal | 80 | ✅ Completado |
| 5 | 21/05/2026 – 03/06/2026 | Autenticación y ABM maestras | normal | 80 | ✅ Completado |
| 6 | 04/06/2026 – 17/06/2026 | Legajo del NNyA | reducida (Parciales) | 56 | ✅ Completado |
| 7 | 18/06/2026 – 01/07/2026 | Informes e intervenciones | reducida (Finales 1er cuatrimestre) | 56 | ✅ Completado |
| 8 | 16/07/2026 – 29/07/2026 | Acompañamiento diario y salud | normal | 80 | ✅ Completado |
| 9 | 30/07/2026 – 12/08/2026 | Incidentes, alertas y turnos | normal | 80 | ✅ Completado |
| 10 | 13/08/2026 – 26/08/2026 | Egreso, tutela y seguimiento | normal | 80 | ✅ Completado |
| 11 | 27/08/2026 – 09/09/2026 | Inicio mobile + reportes SENAF | normal | 80 | ✅ Completado |
| 12 | 10/09/2026 – 23/09/2026 | Mobile F1 + dashboard | normal | 80 | ✅ Completado |
| 13 | 24/09/2026 – 07/10/2026 | Mobile F2/F3 + análisis Didit | reducida (Parciales 2do cuatrimestre) | 56 | ✅ Completado |
| 14 | 08/10/2026 – 21/10/2026 | Mobile F4/F5 + Innovación 1 (Didit) | normal | 80 | ✅ Completado |
| 15 | 22/10/2026 – 04/11/2026 | Mobile F6 + cierre Innovación 1 | normal | 80 | 🔄 En curso |
| 16 | 05/11/2026 – 18/11/2026 | Testing integral y seguridad | reducida (Parciales 2do cuatrimestre) | 56 | ⏳ Planificado |
| 17 | 19/11/2026 – 02/12/2026 | Documentación y despliegue | normal | 80 | ⏳ Planificado |
| 18 | 03/12/2026 – 16/12/2026 | Cierre y defensa | reducida (Mesas de examen) | 56 | ⏳ Planificado |

## Hitos

| Fecha | Hito |
|---|---|
| 06/05/2026 | Fin del análisis: specs 01–12 aprobadas |
| 20/05/2026 | Primer despliegue en Vercel |
| 01/07/2026 | MVP web: ABM maestras + legajo |
| 05/09/2026 | Entrega Unidad I — app mobile |
| 21/10/2026 | Innovación 1 (Didit) integrada |
| 02/12/2026 | Release 1.0 web + mobile |
| 16/12/2026 | Entrega final y defensa |

## Fase 1 — Inicio y análisis

### Sprint 0 — Inicio del proyecto y relevamiento inicial

**12/03/2026 – 25/03/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-001 | Kickoff, conformación del equipo y tablero Scrum en GitHub Projects | Gestión | Jordy | 8 |
| T-002 | Entrevista inicial con la institución y presentación del proyecto | Análisis | Jordy | 12 |
| T-003 | Relevamiento de documentación existente (planillas, legajos en papel) | Análisis | Meli | 10 |
| T-004 | Acta de constitución y alcance preliminar | Gestión | Meli | 10 |
| T-005 | Relevamiento de actores, roles y usuarios del sistema | Análisis | Sofi | 20 |
| T-006 | Relevamiento de herramientas actuales y problemáticas | Análisis | Cami | 12 |
| T-007 | Presentación del proyecto (Encuentro 1) | Documentación | Cami | 8 |

### Sprint 1 — Procesos del negocio

**26/03/2026 – 08/04/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-008 | Proceso de ingreso y admisión (Ley 9944 / Ley 26.061) | Análisis | Jordy | 20 |
| T-009 | Procesos de legajo, documentos e informes | Análisis | Meli | 20 |
| T-010 | Procesos de acompañamiento diario, salud e incidentes | Análisis | Sofi | 20 |
| T-011 | Procesos de egreso, tutela y coordinación judicial / SENAF | Análisis | Cami | 20 |

### Sprint 2 — Requerimientos y modelo de datos

**09/04/2026 – 22/04/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-012 | Modelo de datos (DER) y diccionario de datos | Análisis | Jordy | 20 |
| T-013 | Specs 01–04: acceso y roles, trazabilidad, NNyA y tutores, legajo | Análisis | Sofi | 20 |
| T-014 | Catálogo de excepciones y reglas de negocio | Análisis | Meli | 20 |
| T-015 | Wireframes de baja fidelidad (web) | UX | Cami | 20 |

### Sprint 3 — Arquitectura y especificación funcional

**23/04/2026 – 06/05/2026** · ✅ Completado · Capacidad reducida: Parciales 1er cuatrimestre

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-016 | Arquitectura del sistema (Next.js + Supabase + Expo) v1.1 | Análisis | Jordy | 14 |
| T-017 | Specs 05–08: documentos, informes, salud, acompañamiento diario | Análisis | Sofi | 14 |
| T-018 | Specs 09–12: incidentes, egreso, coordinación judicial, evaluación | Análisis | Meli | 14 |
| T-019 | Prototipo de alta fidelidad y guía de estilos | UX | Cami | 14 |

## Fase 2 — Construcción web

### Sprint 4 — Setup técnico y sistema de diseño

**07/05/2026 – 20/05/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-020 | Setup Next.js + Supabase + Vercel y migraciones iniciales | Web | Jordy | 20 |
| T-021 | Sistema de diseño: tokens y componentes base | Web | Cami | 20 |
| T-022 | Plan de pruebas y criterios de aceptación | QA | Meli | 14 |
| T-023 | Estimación por Puntos de Función (PF sin ajustar) | Gestión | Meli | 6 |
| T-024 | Plan de trabajo ISO 12207 y línea base de valor ganado | Documentación | Sofi | 20 |

### Sprint 5 — Autenticación y ABM maestras

**21/05/2026 – 03/06/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-025 | Autenticación, roles y políticas RLS base | Web | Jordy | 20 |
| T-026 | Layout, navegación y ABM de usuarios y roles | Web | Cami | 20 |
| T-027 | ABM de NNyA y tutores | Web | Sofi | 20 |
| T-028 | Pruebas manuales del sprint y datos de prueba (seed) | QA | Meli | 20 |

### Sprint 6 — Legajo del NNyA

**04/06/2026 – 17/06/2026** · ✅ Completado · Capacidad reducida: Parciales

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-029 | Legajos: alta, estados y vínculo NNyA–tutor (BD + RLS) | Web | Jordy | 14 |
| T-030 | Pantallas de legajo y detalle de NNyA | Web | Cami | 14 |
| T-031 | Documentos del legajo (Supabase Storage) | Web | Sofi | 14 |
| T-032 | Pruebas de RLS por rol y regresión | QA | Meli | 14 |

### Sprint 7 — Informes e intervenciones

**18/06/2026 – 01/07/2026** · ✅ Completado · Capacidad reducida: Finales 1er cuatrimestre

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-033 | Módulo de intervenciones (BD + server actions) | Web | Jordy | 14 |
| T-034 | Módulo de informes y exportación a PDF | Web | Sofi | 14 |
| T-035 | Formularios con validación (react-hook-form + Zod) | Web | Cami | 14 |
| T-036 | Pruebas funcionales de informes e intervenciones | QA | Meli | 14 |

> **Receso invernal (sin sprint)** — 02/07/2026 al 15/07/2026.

### Sprint 8 — Acompañamiento diario y salud

**16/07/2026 – 29/07/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-037 | Módulo de actividades / acompañamiento diario | Web | Jordy | 20 |
| T-038 | Módulo de salud (turnos médicos y seguimiento) | Web | Sofi | 20 |
| T-039 | Línea de tiempo del NNyA | Web | Cami | 20 |
| T-040 | Tests unitarios de validaciones | QA | Meli | 20 |

### Sprint 9 — Incidentes, alertas y turnos

**30/07/2026 – 12/08/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-041 | Incidentes y alertas (BD, triggers y API) | Web | Jordy | 20 |
| T-042 | Pantallas de alertas e incidentes | Web | Cami | 20 |
| T-043 | Turnos del personal y tabla de novedades | Web | Sofi | 20 |
| T-044 | Pruebas de integración de la API de incidentes | QA | Meli | 20 |

### Sprint 10 — Egreso, tutela y seguimiento

**13/08/2026 – 26/08/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-045 | Egreso, tutela y referentes | Web | Jordy | 20 |
| T-046 | Seguimiento post-egreso | Web | Sofi | 20 |
| T-047 | Evaluación institucional y propuestas de mejora | Web | Cami | 20 |
| T-048 | Regresión y auditoría de la base de datos | QA | Meli | 20 |

## Fase 3 — Mobile e innovación

### Sprint 11 — Inicio mobile + reportes SENAF

**27/08/2026 – 09/09/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-049 | Setup Expo + NativeWind, modelo de dominio y datos mock (Unidad I) | Mobile | Sofi | 20 |
| T-050 | Componentes UI reutilizables y navegación (auth, tabs) | Mobile | Cami | 20 |
| T-051 | Estado global (Zustand) y capa de datos (React Query) | Mobile | Meli | 20 |
| T-052 | Reportes SENAF y coordinación judicial | Web | Jordy | 20 |

### Sprint 12 — Mobile F1 + dashboard

**10/09/2026 – 23/09/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-053 | Conexión a Supabase, login y F1 — consultar residentes | Mobile | Sofi | 20 |
| T-054 | Sistema de diseño centralizado mobile | Mobile | Cami | 20 |
| T-055 | Dashboard con KPIs y registro de auditoría | Web | Jordy | 20 |
| T-056 | Pruebas de F1 en dispositivos (Expo Go) | QA | Meli | 20 |

### Sprint 13 — Mobile F2/F3 + análisis Didit

**24/09/2026 – 07/10/2026** · ✅ Completado · Capacidad reducida: Parciales 2do cuatrimestre

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-057 | F2 — registrar novedad | Mobile | Sofi | 14 |
| T-058 | F3 — consultar historial de seguimiento | Mobile | Cami | 14 |
| T-059 | Investigación Didit y modelo de datos de retiros (Innovación 1) | Web | Jordy | 14 |
| T-060 | Escenarios de prueba Didit en sandbox | QA | Meli | 14 |

### Sprint 14 — Mobile F4/F5 + Innovación 1 (Didit)

**08/10/2026 – 21/10/2026** · ✅ Completado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-061 | F4 — actividad diaria y F5 — turno y tareas de hoy | Mobile | Sofi | 20 |
| T-062 | Webhook Didit y validación de identidad en retiros | Web | Jordy | 20 |
| T-063 | Pantallas de retiros con QR y alertas educativas | Web | Cami | 20 |
| T-064 | Pruebas de integración y seguridad del webhook | QA | Meli | 20 |

### Sprint 15 — Mobile F6 + cierre Innovación 1

**22/10/2026 – 04/11/2026** · 🔄 En curso

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-065 | F6 — reportar situación crítica y perfil | Mobile | Sofi | 20 |
| T-066 | Alineación de procesos y reglas de estado del legajo | Web | Jordy | 20 |
| T-067 | Ajustes de UX y accesibilidad | Web | Cami | 20 |
| T-068 | Pruebas E2E con Playwright (flujo de retiro) | QA | Meli | 20 |

## Fase 4 — Pruebas, despliegue y cierre

### Sprint 16 — Testing integral y seguridad

**05/11/2026 – 18/11/2026** · ⏳ Planificado · Capacidad reducida: Parciales 2do cuatrimestre

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-069 | Suite de tests completa (unitarios, integración y SQL) | QA | Meli | 14 |
| T-070 | Revisión de seguridad: RLS y hardening | Web | Jordy | 14 |
| T-071 | Pruebas en dispositivos y build EAS (APK) | Mobile | Sofi | 14 |
| T-072 | Corrección de defectos reportados por QA | Web | Cami | 14 |

### Sprint 17 — Documentación y despliegue

**19/11/2026 – 02/12/2026** · ⏳ Planificado

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-073 | Despliegue a producción (Vercel + Supabase) | Web | Jordy | 10 |
| T-074 | Cálculo final de Puntos de Función y valor ganado | Gestión | Jordy | 10 |
| T-075 | Manual de usuario web y mobile | Documentación | Sofi | 20 |
| T-076 | Documentación técnica y diagramas de arquitectura | Documentación | Cami | 20 |
| T-077 | Informe de pruebas y validación con la institución | QA | Meli | 20 |

### Sprint 18 — Cierre y defensa

**03/12/2026 – 16/12/2026** · ⏳ Planificado · Capacidad reducida: Mesas de examen

| ID | Tarea | Área | Responsable | Horas |
|---|---|---|---|---:|
| T-078 | Informe final y preparación de la defensa | Gestión | Jordy | 14 |
| T-079 | Revisión final de entregables ISO 12207 | Documentación | Sofi | 14 |
| T-080 | Presentación y demo | Documentación | Cami | 14 |
| T-081 | Ensayo de la demo y correcciones finales | QA | Meli | 14 |

## Carga por integrante y sprint (horas de tareas)

| Sprint | Jordy | Meli | Cami | Sofi | Total |
|---|---:|---:|---:|---:|---:|
| 0 | 20 | 20 | 20 | 20 | 80 |
| 1 | 20 | 20 | 20 | 20 | 80 |
| 2 | 20 | 20 | 20 | 20 | 80 |
| 3 | 14 | 14 | 14 | 14 | 56 |
| 4 | 20 | 20 | 20 | 20 | 80 |
| 5 | 20 | 20 | 20 | 20 | 80 |
| 6 | 14 | 14 | 14 | 14 | 56 |
| 7 | 14 | 14 | 14 | 14 | 56 |
| 8 | 20 | 20 | 20 | 20 | 80 |
| 9 | 20 | 20 | 20 | 20 | 80 |
| 10 | 20 | 20 | 20 | 20 | 80 |
| 11 | 20 | 20 | 20 | 20 | 80 |
| 12 | 20 | 20 | 20 | 20 | 80 |
| 13 | 14 | 14 | 14 | 14 | 56 |
| 14 | 20 | 20 | 20 | 20 | 80 |
| 15 | 20 | 20 | 20 | 20 | 80 |
| 16 | 14 | 14 | 14 | 14 | 56 |
| 17 | 20 | 20 | 20 | 20 | 80 |
| 18 | 14 | 14 | 14 | 14 | 56 |
