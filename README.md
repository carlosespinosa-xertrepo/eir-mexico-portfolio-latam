# EIR's México · Portfolio de Soluciones Escalables LATAM 2026
> **Xertica.ai** — Plataforma Interactiva & Pitch Deck Ejecutivo para Despliegue Regional

Este proyecto unifica las 4 soluciones de alto impacto desarrolladas por el equipo de **Entrepreneurs in Residence (EIR)** de México, estructuradas de forma concisa, digerible y visualmente atractiva para presentar a **Vanessa Tinoco** y a los directores de país en LATAM (**Colombia, Perú, Chile y México**).

---

## 🎯 Proyectos y Responsables Incluidos

| # | Responsable | Solución / Foco | Objetivo Principal | Resultados & Impacto | Alcance LATAM |
|---|-------------|-----------------|--------------------|----------------------|---------------|
| 1 | **Patricio Martin** | **FinOps & Commits GCP** | Detección de sobredimensionamiento y desvío de commits GCP. | **$120K+ USD** en oportunidades levantadas en 14 cuentas auditadas. | Replicable con BigQuery en Colombia, Perú y Chile en 48 hrs. |
| 2 | **Jorge Caraballo** | **CRM de Envío de Campañas** | Outreach masivo y personalizado para leads de eventos (Summit, SMB). | **140+ leads contactados**, **64% Open Rate** y **28 reuniones agendadas**. | Carga de listas locales en menos de 24 hrs. |
| 3 | **Angel Solis** | **Torre Preventa + Gemini Enterprise** | Monitoreo en vivo de pipeline técnico y radar de desviaciones + **Módulo de Adopción IA**. | **$104K+ USD** priorizados en tiempo real y **82% adopción activa en Gemini**. | Multi-tenant desplegado en Google Cloud Run. |
| 4 | **Carlos Espinosa** | **Salesforce vs Partner Hub (Caso de Éxito)** | Conciliación automatizada entre pipeline CRM y registros de Google Partner Hub. | **$450K+ USD** en incentivos auditados y recuperables; 100% trazabilidad. | Vital para garantizar el cobro oportuno de rebates en toda la región. |

---

## 🚀 Modos de Navegación

1. **🏢 Modo Plataforma & Hub Interactivo (Default):**
   - Navegación por pestañas con fichas ejecutivas ultra-digeribles (Objetivo, ¿En qué ayuda?, Resultados / KPIs, Alcance LATAM).
   - Selector multimedia para cada herramienta:
     - **🎬 Video Demo (35s):** Ranura preparada para grabación de pantalla con preview.
     - **💻 Consola Interactiva:** Simulador funcional con datos de cada herramienta.
     - **✨ Pestaña Gemini:** Módulo especial de adopción de IA en la sección de Angel Solis.
   - Enlace directo a la consola de cada herramienta.
   - Botón `📋 Copiar Resumen` en cada ficha para enviar por chat.

2. **📽️ Modo Slides (Pitch):**
   - Formato idéntico a la presentación editorial Suiza de BanCoppel (`webdeploy-three-orcin.vercel.app`).
   - Controles con teclado: flechas `[←]` `[→]` o barra espaciadora.
   - Animaciones tipográficas de impacto y mosaico Xertica.

---

## ⚡ Cómo Usar y Previsualizar

### Opción 1: Abrir directamente en el navegador
Haz doble clic en el archivo `index.html` o ábrelo desde Chrome / Safari:
```bash
open index.html
```

### Opción 2: Servidor local (Recomendado)
```bash
npx serve . -l 3000
# o alternativamente:
python3 -m http.server 3000
```
Visita en tu navegador: `http://localhost:3000`

---

## 🌐 Despliegue en Vercel (En 1 Minuto)

Si deseas compartir un enlace desplegado en vivo con Vanessa y el equipo:

```bash
# Iniciar sesión y desplegar directamente a producción:
npx vercel --prod
```
*Vercel detectará automáticamente `vercel.json` y generará una URL pública instantánea (ej. `https://eir-portfolio-latam.vercel.app`).*

---

## 📲 Mensaje Listo para Vanessa Tinoco

La plataforma incluye un botón **"📋 Resumen Vanessa"** en la barra superior que abre el mensaje listo para copiar y pegar en Slack o WhatsApp:

```text
Hola Vane! Buen día.

Te compartimos la plataforma interactiva desplegada con los 4 proyectos del equipo EIR México listos para implementarse en LATAM:

🔗 Enlace de la Plataforma:
https://eir-portfolio-latam.vercel.app/ (y en local)

Resumen ejecutivo digerible de cada proyecto:

1. FinOps & GCP Commits (@Patricio Martin)
• Objetivo: Detección proactiva de sobredimensionamiento y control de consumo vs commit.
• En qué ayuda: Evita penalizaciones y genera alertas 90 días antes del fin de contrato para renovaciones con alto margen.
• Resultado / Impacto: $120K+ USD en oportunidades ya levantadas en 14 cuentas auditadas.
• Alcance LATAM: Script de ingesta BigQuery replicable en Colombia, Perú y Chile en 48 hrs.

2. CRM de Envío de Campañas (@Jorge Caraballo)
• Objetivo: Automatizar el outreach masivo y seguimiento comercial de leads de eventos (Summit, SMB, Enterprise).
• En qué ayuda: Envío segmentado con doble llamado a la acción (agendar 1:1 o workshop de IA) sin fricción de TI.
• Resultado / Impacto: 140+ clientes/leads contactados a partir de la información enviada, 64% Open Rate y 28 reuniones agendadas.
• Alcance LATAM: Replicable en 24 hrs para cualquier base comercial local en LATAM.

3. Consola Preventa + Adopción Gemini (@Angel Solis)
• Objetivo: Monitoreo en tiempo real del pipeline técnico de preventa y radar de desviaciones.
• En qué ayuda: Visibilidad 360° en Cloud Run (Firestore live sync) + Pestaña Adicional de Adopción Gemini Enterprise para medir uso de IA y horas ahorradas.
• Resultado / Impacto: $104K+ USD en pipeline priorizado en vivo y 82% de adopción activa en IA.
• Alcance LATAM: Multi-tenant listo en Cloud Run para directores de preventa de toda la región.

4. Cruce Salesforce vs Partner Hub (@Carlos Espinosa - Caso de Éxito)
• Objetivo: Conciliación automatizada entre el pipeline comercial en Salesforce y los incentivos de Google Cloud Partner Hub.
• En qué ayuda: Elimina fuga de incentivos económicos (rebates, fundings) por discrepancias de montos o fechas entre el CRM y Google.
• Resultado / Impacto: $450K+ USD en incentivos auditados y recuperables; 100% trazabilidad.
• Alcance LATAM: Crítico para asegurar el cobro de rebates y margen en todos los países de Xertica.

La plataforma cuenta con 2 modos:
1) Plataforma interactiva con métricas, fichas técnicas y simuladores en vivo
2) Modo Slides (Pitch) para navegar con las flechas del teclado en presentaciones directas.
```

---

## 🎨 Estructura del Proyecto
```
EIR'S México | Portfolio/
├── index.html                 # Aplicación principal interactiva y modo slides
├── vercel.json                # Configuración de despliegue Vercel
├── package.json               # Scripts de desarrollo y despliegue
├── README.md                  # Documentación ejecutiva
└── assets/
    ├── team/                  # Fotos oficiales del equipo EIR México
    │   ├── angel-solis.jpg
    │   ├── carlos-espinosa.jpg
    │   ├── jorge-caraballo.jpg
    │   └── patricio-martin.jpg
    └── projects/              # Capturas y diagramas de las herramientas
        ├── finops-msp-commercial.jpg
        ├── sales-specialist-pipeline.jpg
        ├── torre-control-preventa.jpg
        └── eir-projects-showcase.jpg
```
