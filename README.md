cd ~/n8n-workflows-compendium

# 2) Crear carpeta para capturas (y dejarla trackeada)
mkdir -p assets/screenshots
touch assets/screenshots/.gitkeep

# 1) Reemplazar README.md (bilingüe / portafolio)
cat > README.md << 'EOF'
# n8n Workflows Compendium — Portfolio | Portafolio (ES/EN)

👋 **ES:** Soy **Andrés Celemin Cardoso**. Este repositorio es mi 
portafolio de automatización con **n8n**: workflows reutilizables para 
ventas, soporte, agendamiento, integraciones por API y agentes de IA.  
👋 **EN:** I'm **Andrés Celemin Cardoso**. This repository is my 
automation portfolio built with **n8n**: reusable workflows for sales, 
support, scheduling, API integrations, and AI agents.

---

## 🔥 Highlights | Destacados

**ES**
- ✅ Compendio de **2000+ exports** de workflows (organizados por 
categorías)
- ✅ Enfoque en **ROI rápido**: menos trabajo manual, más conversiones, 
mejor experiencia del cliente
- ✅ Integraciones comunes: Webhooks, HTTP/API, Sheets, CRMs, soporte, 
scraping, etc.

**EN**
- ✅ Compendium of **2000+ workflow exports** (organized by category)
- ✅ Focused on **fast ROI**: reduce manual work, increase conversions, 
improve customer experience
- ✅ Common integrations: Webhooks, HTTP/API, Sheets, CRMs, support, 
scraping, etc.

---

## 🧠 What I do | Qué hago

**ES**
Diseño e implemento automatizaciones end-to-end con n8n: captura de leads 
→ calificación → follow-ups → CRM → reportes.  
Trabajo con **prompt engineering** e **integraciones por API** para 
conectar IA con procesos reales.

**EN**
I design and ship end-to-end n8n automations: lead capture → 
qualification → follow-ups → CRM → reporting.  
I combine **prompt engineering** and **API integrations** to connect AI 
with real business workflows.

---

## 🧰 Tech Stack | Tecnologías

- **n8n** (workflows, webhooks, routing, error handling)
- **HTTP / REST APIs**, OAuth, Webhooks
- Integraciones frecuentes: Google Sheets, CRMs, Helpdesk, Scraping tools, 
etc.
- (Optional) Databases/CRM: PostgreSQL/Supabase, Airtable, Notion (según 
proyecto)

---

## 📁 Repository Structure | Estructura del repositorio

```text
workflows/
  n8n/
    workflows/
      <Category>/
        <WorkflowName>.json
assets/
  screenshots/
docs/
templates/

