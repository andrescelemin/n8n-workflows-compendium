n8n Workflows Compendium — Automation Portfolio (ES / EN)

Author: Andrés Celemin Cardoso
Focus: Automation, AI Agents, Business Workflows
Primary Tooling: n8n + APIs

==================================================

OVERVIEW | VISIÓN GENERAL

ES
Este repositorio es un compendio profesional de automatizaciones desarrolladas con n8n.
Funciona como portafolio técnico y biblioteca reutilizable de workflows listos para producción, enfocados en ventas, soporte, agendamiento, integraciones por API y agentes de IA.

El objetivo es claro: reducir trabajo manual, mejorar eficiencia operativa y generar ROI medible desde el primer día.

EN
This repository is a professional compendium of automations built with n8n.
It serves as both a technical portfolio and a reusable library of production-ready workflows focused on sales, support, scheduling, API integrations, and AI agents.

The goal is simple: reduce manual work, improve operational efficiency, and deliver measurable ROI from day one.

==================================================

KEY HIGHLIGHTS | PUNTOS CLAVE

ES
- Más de 2000 workflows exportados y organizados por categorías funcionales.
- Automatizaciones orientadas a negocio y resultados reales, no solo pruebas técnicas.
- Diseño modular y reutilizable, fácil de adaptar a distintos entornos.
- Integraciones frecuentes con herramientas reales de producción.

EN
- 2000+ exported workflows organized by functional categories.
- Business-oriented automations focused on real outcomes, not demos.
- Modular and reusable design, easy to adapt to different environments.
- Integrations with real-world production tools.

==================================================

WHAT I BUILD | QUÉ DESARROLLO

ES
Diseño e implemento automatizaciones end-to-end con n8n, cubriendo flujos completos como:

- Captura y normalización de leads
- Calificación automática y enrute inteligente
- Follow-ups multicanal
- Sincronización con CRM y bases de datos
- Generación de reportes y eventos

Integro agentes de IA mediante prompt engineering y APIs para que la automatización no solo ejecute tareas, sino que también tome decisiones guiadas por reglas y contexto.

EN
I design and implement end-to-end automations with n8n, covering full workflows such as:

- Lead capture and normalization
- Automated qualification and smart routing
- Multichannel follow-ups
- CRM and database synchronization
- Reporting and event generation

I integrate AI agents using prompt engineering and APIs so automations do not just execute tasks, but also make context-aware decisions.

==================================================

TECH STACK | STACK TECNOLÓGICO

Core
- n8n (workflows, triggers, routing, retries, error handling, scheduling)

Integrations
- HTTP / REST APIs
- Webhooks
- OAuth-based services

Common Platforms
- Google Sheets and Google Workspace
- CRMs and Helpdesk systems
- Scraping and data extraction tools

Databases (optional depending on use case)
- PostgreSQL
- Supabase
- Airtable
- Notion

==================================================

REPOSITORY STRUCTURE | ESTRUCTURA DEL REPOSITORIO

workflows/
  n8n/
    workflows/
      <Category>/
        <WorkflowName>.json

assets/
  screenshots/

docs/
templates/

==================================================

QUICK START | INICIO RÁPIDO

ES

1. Selecciona un workflow del repositorio.
   Ejemplo: workflows/n8n/workflows/Http/

2. En n8n, importa el archivo:
   Workflows → Import from file → selecciona el .json

3. Revisa el workflow:
   - Credenciales (HTTP, Google, AWS, bases de datos, etc.)
   - Variables y parámetros (URLs, IDs, tablas, colas)
   - Tipo de trigger (Webhook, Cron, Scheduled)

4. Ejecuta una prueba controlada:
   - Webhook: envía un payload de prueba con Postman o cURL.
   - Cron/Scheduled: usa "Run once" para validar.

5. Activa el workflow cuando esté validado:
   Active = ON

EN

1. Select a workflow from the repository.
   Example: workflows/n8n/workflows/Http/

2. Import it into n8n:
   Workflows → Import from file → select the .json

3. Review the workflow:
   - Credentials (HTTP, Google, AWS, databases, etc.)
   - Variables and parameters (URLs, IDs, tables, queues)
   - Trigger type (Webhook, Cron, Scheduled)

4. Run a controlled test:
   - Webhook: send a test payload using Postman or cURL.
   - Cron/Scheduled: use "Run once".

5. Enable the workflow once validated:
   Active = ON

==================================================

FEATURED WORKFLOWS | WORKFLOWS DESTACADOS

Folder:
workflows/n8n/workflows/Http/

- HTTP Cron Update (Webhook)
- AWS SQS Automation (Scheduled)
- Google BigQuery Automation (Scheduled)
- MQTT Automation (Webhook)
- HTML Extract and Create (Webhook)
- Noop Sync (Webhook)
- HTTP Cron Automation (Webhook)
- GitHub Create (Scheduled)
- Firebase Realtime Database Update (Webhook)
- MySQL Automation (Webhook)

==================================================

SECURITY & CREDENTIALS | SEGURIDAD

ES
Este repositorio no incluye secretos ni credenciales.
Todas las credenciales deben configurarse localmente en n8n mediante el Credential Manager.

EN
This repository does not include secrets or credentials.
All credentials must be configured locally in n8n using the Credential Manager.

==================================================

CONTACT | CONTACTO

Andrés Celemin Cardoso

GitHub
https://github.com/andrescelemin

Website
https://agentes-inteligencia-artificial.online/

LinkedIn
https://www.linkedin.com/in/andr%C3%A9s-celem%C3%ADn-391a43387/

==================================================

This repository reflects a practical, production-focused approach to automation,
combining AI, APIs, and workflow orchestration to solve real business problems.
