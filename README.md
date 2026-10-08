<a href="https://lumidev.vercel.app">
  <img src="./assets/banner.svg" alt="LumiDev — Luis Miranda, AI & Automation Specialist" width="100%" />
</a>

<p align="center">
  <a href="https://lumidev.vercel.app"><img src="https://img.shields.io/badge/Portafolio-lumidev.vercel.app-22D3EE?style=flat-square&labelColor=0A0E14" alt="Portafolio" /></a>
  <a href="https://www.linkedin.com/in/luis-miranda-de-la-guarda/"><img src="https://img.shields.io/badge/LinkedIn-Luis%20Miranda-22D3EE?style=flat-square&logo=linkedin&logoColor=white&labelColor=0A0E14" alt="LinkedIn" /></a>
  <a href="mailto:lumidev.contact@gmail.com"><img src="https://img.shields.io/badge/Email-lumidev.contact%40gmail.com-22D3EE?style=flat-square&logo=gmail&logoColor=white&labelColor=0A0E14" alt="Email" /></a>
</p>

## Hola, soy Luis Miranda 👋

**AI & Automation Specialist** y **Coordinador de Desarrollo de Plataforma Educativa (LMS)** en una institución de educación superior online en Chile.

Convierto procesos manuales de operación académica en sistemas **automáticos, auditables y de autoservicio**: integro el sistema académico con Blackboard Learn, automatizo operaciones masivas por API y construyo reportería y alarmas. La IA no es un adorno en mi trabajo, es mi método.

> 🌐 Todo el detalle, con casos de estudio y blog, está en **[lumidev.vercel.app](https://lumidev.vercel.app)**.

## En números

| | |
|---|---|
| **15** | integraciones activas en producción entre el sistema académico y Blackboard |
| **7** | reportes y alarmas automáticos sobre la base de datos de Blackboard |
| **759** | tablas del esquema legacy documentadas en un índice consultable |

## Qué hago

- 🔄 **Integraciones y ETL:** sincronizo altas y bajas de alumnos y docentes entre el SIS y el LMS, con alarmas cuando algo no cuadra.
- 📊 **Reportería y datos:** reportes recurrentes que se arman solos y dashboards listos para decidir (Snowflake, Power BI, SQL).
- 🧩 **Apps internas y autoservicio:** herramientas para que áreas no técnicas resuelvan solas lo que antes pedían por correo.
- 🤖 **IA aplicada a operaciones:** Claude Code, skills reutilizables, agentes y flujos con n8n.

## Casos destacados

| Caso | Qué resuelve |
|---|---|
| [Sincronización SIS ↔ Blackboard](https://lumidev.vercel.app/proyectos/sincronizacion-sis-lms) | ETL en Python con cruce por RUT + ramo + sección, ramas Git por bimestre y alarma de diferencias. |
| [Migración de reportería a Snowflake](https://lumidev.vercel.app/proyectos/migracion-reporteria-snowflake) | Índice de 759 tablas, mapeo DDA → CDM_LMS y gestión del cambio con el modelo Kotter. |
| [Reportería académica automatizada](https://lumidev.vercel.app/proyectos/reporteria-academica-automatizada) | Reportes bimestrales de notas, auditorías del gradebook y pipeline hacia Power BI. |
| [Apps sobre la API de Blackboard](https://lumidev.vercel.app/proyectos/automatizacion-api-blackboard) | Aulas desde plantillas, apertura y cierre masivo de cursos, contenidos y reglas de liberación. |

👉 [Ver todos los casos](https://lumidev.vercel.app/proyectos)

## Open source en construcción 🚧

Versiones públicas de mis herramientas, reconstruidas desde cero con datos sintéticos:

- **`lms-sync-kit`**: ETL genérico SIS ↔ LMS con diff de altas y bajas, y alarma de diferencias.
- **`gradebook-reports`**: CLI de reportes de notas (vacías, pendientes, consolidación xlsx, escala 1–7).
- **`grades-self-service`**: app FastAPI + React para buscar y descargar notas en CSV a gran escala.
- **`lms-claude-skills`**: skills y prompts de Claude, y plantillas n8n para la operación de un LMS.
- **`lms-ops-agent`**: agente de operaciones de plataforma con la API de Claude.

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,postgres,mongodb,fastapi,react,nextjs,ts,tailwind,docker,aws,linux,git&theme=dark" alt="Stack" />
</p>

**Datos:** Python (pandas, psycopg2) · SQL · PostgreSQL · SQL Server · Snowflake<br/>
**Integración y BI:** Blackboard Learn REST API · n8n · Power BI · SharePoint<br/>
**IA:** Claude Code · Claude API · skills y agentes

## Cómo trabajo

```text
01 Planificar  → defino alcance y riesgos antes de tocar código (Claude Code en modo Plan)
02 Revisar     → reviso el plan y el diff como con un compañero; todo pasa primero por test
03 Ejecutar    → implemento en modo automático, con ramas por período o tipo de carga
04 Empaquetar  → si un flujo se repite, lo convierto en skill o script reutilizable
```

## Trayectoria

- **Coordinador de Desarrollo Plataforma Educativa / LMS**, institución de educación superior online · *may 2025 — actualidad*
- **Ingeniero de Monitoreo y Postventa**, Embedx · *ene 2025 — jun 2025*
- **Asistente de Investigación**, RisLab UOH · visión por computador para el monitoreo de la producción de cerezas (segmentación hiperespectral) · *2024*
- **Ayudante docente**, Ing. Civil en Computación UOH · Minería de Datos, Interacción Humano-Computador · *2023 — 2024*
- **Práctica profesional en Análisis de Datos y Automatización**, Copec S.A. · automatización de la conciliación de órdenes de compra y facturas electrónicas · *2022 — 2023*
- **Ingeniería Civil en Computación**, Universidad de O'Higgins · *2018 — 2024*

## Últimas notas del blog

- [Mi flujo con Claude Code en producción: plan, revisión y modo automático](https://lumidev.vercel.app/blog/mi-flujo-con-claude-code)
- [Documentar 759 tablas para no reaprender errores](https://lumidev.vercel.app/blog/documentar-para-no-reaprender)

---

<p align="center">
  ¿Tienes un proceso que debería funcionar solo? <a href="https://lumidev.vercel.app/#contacto">Conversemos</a>.<br/>
  <sub>Fuera del código, soy músico y compositor 🎵</sub>
</p>
