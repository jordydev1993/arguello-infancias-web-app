# Diagrama de Gantt — Argüello Infancias — Sistema de gestión de residencia NNyA (web + mobile)

GitHub dibuja este diagrama automáticamente. Las tareas detalladas están en `SPRINTS.md`.

```mermaid
gantt
    title Argüello Infancias — web y mobile
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    todayMarker on
    section Inicio y análisis
    S0 Inicio del proyecto y relevamiento inicial :done, s0, 2026-03-12, 2026-03-25
    S1 Procesos del negocio :done, s1, 2026-03-26, 2026-04-08
    S2 Requerimientos y modelo de datos :done, s2, 2026-04-09, 2026-04-22
    S3 Arquitectura y especificación funcional :done, s3, 2026-04-23, 2026-05-06
    section Construcción web
    S4 Setup técnico y sistema de diseño :done, s4, 2026-05-07, 2026-05-20
    S5 Autenticación y ABM maestras :done, s5, 2026-05-21, 2026-06-03
    S6 Legajo del NNyA :done, s6, 2026-06-04, 2026-06-17
    S7 Informes e intervenciones :done, s7, 2026-06-18, 2026-07-01
    Receso invernal :crit, 2026-07-02, 2026-07-15
    S8 Acompañamiento diario y salud :done, s8, 2026-07-16, 2026-07-29
    S9 Incidentes, alertas y turnos :done, s9, 2026-07-30, 2026-08-12
    S10 Egreso, tutela y seguimiento :done, s10, 2026-08-13, 2026-08-26
    section Mobile e innovación
    S11 Inicio mobile + reportes SENAF :done, s11, 2026-08-27, 2026-09-09
    S12 Mobile F1 + dashboard :done, s12, 2026-09-10, 2026-09-23
    S13 Mobile F2/F3 + análisis Didit :done, s13, 2026-09-24, 2026-10-07
    S14 Mobile F4/F5 + Innovación 1 (Didit) :done, s14, 2026-10-08, 2026-10-21
    S15 Mobile F6 + cierre Innovación 1 :active, s15, 2026-10-22, 2026-11-04
    section Pruebas, despliegue y cierre
    S16 Testing integral y seguridad :s16, 2026-11-05, 2026-11-18
    S17 Documentación y despliegue :s17, 2026-11-19, 2026-12-02
    S18 Cierre y defensa :s18, 2026-12-03, 2026-12-16
    section Hitos
    Fin del análisis — specs 01–12 aprobadas :milestone, 2026-05-06, 0d
    Primer despliegue en Vercel :milestone, 2026-05-20, 0d
    MVP web — ABM maestras + legajo :milestone, 2026-07-01, 0d
    Entrega Unidad I — app mobile :milestone, 2026-09-05, 0d
    Innovación 1 (Didit) integrada :milestone, 2026-10-21, 0d
    Release 1.0 web + mobile :milestone, 2026-12-02, 0d
    Entrega final y defensa :milestone, 2026-12-16, 0d
```

## Jordy

```mermaid
gantt
    title Tareas de Jordy
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    section Inicio y análisis
    Kickoff, conformación del equipo y tablero Scrum en GitHub Projects (8 h) :done, 2026-03-12, 2026-03-25
    Entrevista inicial con la institución y presentación del proyecto (12 h) :done, 2026-03-12, 2026-03-25
    Proceso de ingreso y admisión (Ley 9944 / Ley 26.061) (20 h) :done, 2026-03-26, 2026-04-08
    Modelo de datos (DER) y diccionario de datos (20 h) :done, 2026-04-09, 2026-04-22
    Arquitectura del sistema (Next.js + Supabase + Expo) v1.1 (14 h) :done, 2026-04-23, 2026-05-06
    section Construcción web
    Setup Next.js + Supabase + Vercel y migraciones iniciales (20 h) :done, 2026-05-07, 2026-05-20
    Autenticación, roles y políticas RLS base (20 h) :done, 2026-05-21, 2026-06-03
    Legajos  alta, estados y vínculo NNyA–tutor (BD + RLS) (14 h) :done, 2026-06-04, 2026-06-17
    Módulo de intervenciones (BD + server actions) (14 h) :done, 2026-06-18, 2026-07-01
    Módulo de actividades / acompañamiento diario (20 h) :done, 2026-07-16, 2026-07-29
    Incidentes y alertas (BD, triggers y API) (20 h) :done, 2026-07-30, 2026-08-12
    Egreso, tutela y referentes (20 h) :done, 2026-08-13, 2026-08-26
    section Mobile e innovación
    Reportes SENAF y coordinación judicial (20 h) :done, 2026-08-27, 2026-09-09
    Dashboard con KPIs y registro de auditoría (20 h) :done, 2026-09-10, 2026-09-23
    Investigación Didit y modelo de datos de retiros (Innovación 1) (14 h) :done, 2026-09-24, 2026-10-07
    Webhook Didit y validación de identidad en retiros (20 h) :done, 2026-10-08, 2026-10-21
    Alineación de procesos y reglas de estado del legajo (20 h) :active, 2026-10-22, 2026-11-04
    section Pruebas, despliegue y cierre
    Revisión de seguridad  RLS y hardening (14 h) :2026-11-05, 2026-11-18
    Despliegue a producción (Vercel + Supabase) (10 h) :2026-11-19, 2026-12-02
    Cálculo final de Puntos de Función y valor ganado (10 h) :2026-11-19, 2026-12-02
    Informe final y preparación de la defensa (14 h) :2026-12-03, 2026-12-16
```

## Meli

```mermaid
gantt
    title Tareas de Meli
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    section Inicio y análisis
    Relevamiento de documentación existente (planillas, legajos en papel) (10 h) :done, 2026-03-12, 2026-03-25
    Acta de constitución y alcance preliminar (10 h) :done, 2026-03-12, 2026-03-25
    Procesos de legajo, documentos e informes (20 h) :done, 2026-03-26, 2026-04-08
    Catálogo de excepciones y reglas de negocio (20 h) :done, 2026-04-09, 2026-04-22
    Specs 09–12  incidentes, egreso, coordinación judicial, evaluación (14 h) :done, 2026-04-23, 2026-05-06
    section Construcción web
    Plan de pruebas y criterios de aceptación (14 h) :done, 2026-05-07, 2026-05-20
    Estimación por Puntos de Función (PF sin ajustar) (6 h) :done, 2026-05-07, 2026-05-20
    Pruebas manuales del sprint y datos de prueba (seed) (20 h) :done, 2026-05-21, 2026-06-03
    Pruebas de RLS por rol y regresión (14 h) :done, 2026-06-04, 2026-06-17
    Pruebas funcionales de informes e intervenciones (14 h) :done, 2026-06-18, 2026-07-01
    Tests unitarios de validaciones (20 h) :done, 2026-07-16, 2026-07-29
    Pruebas de integración de la API de incidentes (20 h) :done, 2026-07-30, 2026-08-12
    Regresión y auditoría de la base de datos (20 h) :done, 2026-08-13, 2026-08-26
    section Mobile e innovación
    Estado global (Zustand) y capa de datos (React Query) (20 h) :done, 2026-08-27, 2026-09-09
    Pruebas de F1 en dispositivos (Expo Go) (20 h) :done, 2026-09-10, 2026-09-23
    Escenarios de prueba Didit en sandbox (14 h) :done, 2026-09-24, 2026-10-07
    Pruebas de integración y seguridad del webhook (20 h) :done, 2026-10-08, 2026-10-21
    Pruebas E2E con Playwright (flujo de retiro) (20 h) :active, 2026-10-22, 2026-11-04
    section Pruebas, despliegue y cierre
    Suite de tests completa (unitarios, integración y SQL) (14 h) :2026-11-05, 2026-11-18
    Informe de pruebas y validación con la institución (20 h) :2026-11-19, 2026-12-02
    Ensayo de la demo y correcciones finales (14 h) :2026-12-03, 2026-12-16
```

## Cami

```mermaid
gantt
    title Tareas de Cami
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    section Inicio y análisis
    Relevamiento de herramientas actuales y problemáticas (12 h) :done, 2026-03-12, 2026-03-25
    Presentación del proyecto (Encuentro 1) (8 h) :done, 2026-03-12, 2026-03-25
    Procesos de egreso, tutela y coordinación judicial / SENAF (20 h) :done, 2026-03-26, 2026-04-08
    Wireframes de baja fidelidad (web) (20 h) :done, 2026-04-09, 2026-04-22
    Prototipo de alta fidelidad y guía de estilos (14 h) :done, 2026-04-23, 2026-05-06
    section Construcción web
    Sistema de diseño  tokens y componentes base (20 h) :done, 2026-05-07, 2026-05-20
    Layout, navegación y ABM de usuarios y roles (20 h) :done, 2026-05-21, 2026-06-03
    Pantallas de legajo y detalle de NNyA (14 h) :done, 2026-06-04, 2026-06-17
    Formularios con validación (react-hook-form + Zod) (14 h) :done, 2026-06-18, 2026-07-01
    Línea de tiempo del NNyA (20 h) :done, 2026-07-16, 2026-07-29
    Pantallas de alertas e incidentes (20 h) :done, 2026-07-30, 2026-08-12
    Evaluación institucional y propuestas de mejora (20 h) :done, 2026-08-13, 2026-08-26
    section Mobile e innovación
    Componentes UI reutilizables y navegación (auth, tabs) (20 h) :done, 2026-08-27, 2026-09-09
    Sistema de diseño centralizado mobile (20 h) :done, 2026-09-10, 2026-09-23
    F3 — consultar historial de seguimiento (14 h) :done, 2026-09-24, 2026-10-07
    Pantallas de retiros con QR y alertas educativas (20 h) :done, 2026-10-08, 2026-10-21
    Ajustes de UX y accesibilidad (20 h) :active, 2026-10-22, 2026-11-04
    section Pruebas, despliegue y cierre
    Corrección de defectos reportados por QA (14 h) :2026-11-05, 2026-11-18
    Documentación técnica y diagramas de arquitectura (20 h) :2026-11-19, 2026-12-02
    Presentación y demo (14 h) :2026-12-03, 2026-12-16
```

## Sofi

```mermaid
gantt
    title Tareas de Sofi
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    section Inicio y análisis
    Relevamiento de actores, roles y usuarios del sistema (20 h) :done, 2026-03-12, 2026-03-25
    Procesos de acompañamiento diario, salud e incidentes (20 h) :done, 2026-03-26, 2026-04-08
    Specs 01–04  acceso y roles, trazabilidad, NNyA y tutores, legajo (20 h) :done, 2026-04-09, 2026-04-22
    Specs 05–08  documentos, informes, salud, acompañamiento diario (14 h) :done, 2026-04-23, 2026-05-06
    section Construcción web
    Plan de trabajo ISO 12207 y línea base de valor ganado (20 h) :done, 2026-05-07, 2026-05-20
    ABM de NNyA y tutores (20 h) :done, 2026-05-21, 2026-06-03
    Documentos del legajo (Supabase Storage) (14 h) :done, 2026-06-04, 2026-06-17
    Módulo de informes y exportación a PDF (14 h) :done, 2026-06-18, 2026-07-01
    Módulo de salud (turnos médicos y seguimiento) (20 h) :done, 2026-07-16, 2026-07-29
    Turnos del personal y tabla de novedades (20 h) :done, 2026-07-30, 2026-08-12
    Seguimiento post-egreso (20 h) :done, 2026-08-13, 2026-08-26
    section Mobile e innovación
    Setup Expo + NativeWind, modelo de dominio y datos mock (Unidad I) (20 h) :done, 2026-08-27, 2026-09-09
    Conexión a Supabase, login y F1 — consultar residentes (20 h) :done, 2026-09-10, 2026-09-23
    F2 — registrar novedad (14 h) :done, 2026-09-24, 2026-10-07
    F4 — actividad diaria y F5 — turno y tareas de hoy (20 h) :done, 2026-10-08, 2026-10-21
    F6 — reportar situación crítica y perfil (20 h) :active, 2026-10-22, 2026-11-04
    section Pruebas, despliegue y cierre
    Pruebas en dispositivos y build EAS (APK) (14 h) :2026-11-05, 2026-11-18
    Manual de usuario web y mobile (20 h) :2026-11-19, 2026-12-02
    Revisión final de entregables ISO 12207 (14 h) :2026-12-03, 2026-12-16
```
