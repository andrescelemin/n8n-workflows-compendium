cd ~/n8n-workflows-compendium

cat > README.md << 'EOF'
# n8n Workflows Compendium — Portfolio | Portafolio (ES/EN)


👋 **ES:** Soy **Andrés Celemin Cardoso**. Este repositorio es mi portafolio de automatización con **n8n**: workflows reutilizables para ventas, soporte, agendamiento, integraciones por API y agentes de IA.  
👋 **EN:** I'm **Andrés Celemin Cardoso**. This repository is my automation portfolio built with **n8n**: reusable workflows for sales, support, scheduling, API integrations, and AI agents.

👋 **ES:** Soy **Andrés Celemin Cardoso**. Este repositorio es mi 
portafolio de automatización con **n8n**: workflows reutilizables para 
ventas, soporte, agendamiento, integraciones por API y agentes de IA.  
👋 **EN:** I'm **Andrés Celemin Cardoso**. This repository is my 
automation portfolio built with **n8n**: reusable workflows for sales, 
support, scheduling, API integrations, and AI agents.

🚀 Quick Start | Inicio rápido

ES

n8n → Workflows → Import from file

Selecciona el .json

Ajusta credenciales/variables y prueba

EN

n8n → Workflows → Import from file

Select the .json

Configure credentials/variables and test

🔐 Security & Secrets | Seguridad y secretos

ES

No se incluyen credenciales reales.

Reemplaza tokens por placeholders (ej: Bearer {{API_KEY}}).

EN

No real credentials are included.

Replace tokens with placeholders (e.g., Bearer {{API_KEY}}).

📬 Contact / Contacto

Andrés Celemin
GitHub: @andrescelemin
Website: https://agentes-inteligencia-artificial.online/
Email: smart.consulting@agentes-inteligencia-artificial.online
LinkedIn: https://www.linkedin.com/in/andr%C3%A9s-celem%C3%ADn-391a43387/
EOF

git add README.md
git commit -m "Fix README content"
git push
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
>>>>>>> b884044 (Update README)

---

## 🧰 Tech Stack | Tecnologías

- **n8n** (workflows, webhooks, routing, error handling)
- **HTTP / REST APIs**, OAuth, Webhooks
- Integraciones frecuentes: Google Sheets, CRMs, Helpdesk, Scraping tools, etc.
- Databases/CRM (optional): PostgreSQL/Supabase, Airtable, Notion

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
