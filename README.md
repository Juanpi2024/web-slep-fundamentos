# README.md — Ecosistema Antigravity V2

> "La organización es la clave de la victoria. La soberanía digital es el fin." ✊

---

## 🧠 ¿Qué es Antigravity?

Antigravity es un ecosistema de inteligencia artificial orquestada diseñado para la producción, gestión y distribución automatizada de material educativo. Opera bajo un modelo híbrido que separa las capacidades cognitivas (orquestación) de la ejecución técnica (disk operations).

---

## 📋 Arquitectura del Sistema

```
┌─────────────────────────────────────────────────────────────┐
│                    COMANDANTE JUAN PABLO                     │
│              (Emisor de Órdenes / Prompting)                 │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│              ANTINGRAVITY: EL CEREBRO 🧠                     │
│   Orquestación semántica, planificación, redacción premium   │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│               CLAWDBOT: LAS MANOS 🦾                         │
│    Ejecución Powershell, filesystem local, APIs remotas      │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                  ORQUESTA ROJA (14 Agentes)                  │
│         Especialización táctica por dominio funcional        │
└─────────────────────────────────────────────────────────────┘
```

---

## 🎯 Los 14 Agentes Tácticos

| # | Agente | Alias | Función Principal |
|---|--------|-------|-------------------|
| 1 | **Rojo** | Fidel | Director y delegador supremo |
| 2 | **Gramsci** | — | Analista curricular (Drive vs Local) |
| 3 | **Stalin** | Custodio | Limpieza de metadatos y sanitización |
| 4 | **Che Guevara** | — | Pedagogo DUA y diseño instruccional |
| 5 | **Lenin** | — | Publicador automatizado en ProfeSocial |
| 6 | **Putin** | Nexo | Agente de inteligencia (email monitoring) |
| 7 | **Pepe Mujica** | — | Diplomático y humanizador de textos |
| 8 | **Gladys Marín** | — | Investigadora legal y regulatoria |
| 9 | **Allende** | — | Soporte CRM y atención comunitaria |
| 10 | **Xi Jinping** | — | Gestor financiero y OCR de boletas |
| 11 | **Chávez** | — | Marketing y redes sociales |
| 12 | **Mao** | — | Arquitecto de encuestas y dashboards |
| 13 | **Leo** | — | Diseñador de gamificación |
| 14 | **Keynote** | — | Generador de presentaciones PowerPoint |

---

## 📁 Estructura de Directorios

```
/workspace/
├── MANIFIESTO_V2.md           # Documento maestro de arquitectura
├── MEMORY.md                  # Memoria curada (rutas, APIs, precios)
├── agents/                    # 14 agentes tácticos
│   ├── rojo_comunicaciones/
│   ├── analista_curriculum/
│   ├── limpieza_datos/
│   ├── pedagogico/
│   ├── publicador_profesocial/
│   ├── asistente_personal/
│   ├── pepe_diplomacia/
│   ├── gladys_marin/
│   ├── soporte_crm/
│   ├── gestor_financiero/
│   ├── marketing/
│   ├── especialista_encuestas/
│   └── powerpoint_expert/
├── apps/                      # Aplicaciones interactivas
│   └── explorador-tierra/     # Framework de gamificación
└── memory/                    # Protocolo de memoria activa
    ├── heartbeat-state.json   # Estado de latidos automáticos
    └── YYYY-MM-DD.md          # Notas diarias de sesión
```

---

## 💓 Ciclo de Heartbeats

El sistema ejecuta latidos automáticos cada **30 minutos** para:

1. Consultar último estado en `memory/heartbeat-state.json`
2. Monitorear bandeja de entrada y ventas
3. Alertar sobre ingresos en ProfeSocial / Escuela
4. Sincronizar Google Sheets de clientes
5. Actualizar timestamp y logs

---

## 🔒 Políticas de Seguridad

### ⚠️ Destrucción Permanente Prohibida
- **NUNCA** usar `rm` en Powershell
- **SIEMPRE** usar papelera de reciclaje (`trash`)

### 🔐 Credenciales
- Jamás subir `.env` a repositorios públicos
- Mantener APIs de Google/OpenAI fuera de GitHub

---

## 🚀 Flujo de Producción Típico

```
Comandante → Rojo → Stalin → Che Guevara → Lenin → ProfeSocial → Putin
   │           │        │          │           │         │           │
   │           │        │          │           │         │           └─→ Notifica venta
   │           │        │          │           │         └─→ Publica a 6 ProfeCoins
   │           │        │          │           └─→ Automatiza carga con SEO
   │           │        │          └─→ Diseña guía DUA + solucionario
   │           │        └─→ Limpia metadatos del Word
   │           └─→ Delega al especialista correcto
   └─→ Envía orden compleja
```

---

## 📞 Fórmulas de Invocación

Cada agente responde a fórmulas específicas. Ejemplos:

- **Rojo:** *"Rojo, delega a Stalin la sanitización de los últimos documentos subidos."*
- **Gramsci:** *"Gramsci, escanea el Drive y repórtame qué unidades de Ciencias de 4to Básico nos faltan en local."*
- **Che Guevara:** *"Che Guevara, toma esta planificación de Lenguaje y diséñame la guía del estudiante con estrategias DUA."*
- **Lenin:** *"Lenin, sube la carpeta de evaluaciones de Matemáticas a ProfeSocial a 6 ProfeCoins con sus tags."*
- **Pepe Mujica:** *"Pepe, redacta una carta al director del colegio explicando el retraso del reporte escolar, con tu estilo humilde."*

Ver `MANIFIESTO_V2.md` para el listado completo.

---

## 🛠️ Instalación y Configuración

### Prerrequisitos
- Node.js (v18+)
- Python 3.x
- PowerShell (Windows) o Bash (Linux/Mac)

### Dependencias Globales
```bash
npm install -g playwright puppeteer
pip install python-docx adm-zip pptxgenjs openpyxl tesseract
```

### Variables de Entorno (.env)
```env
# Google APIs
GOOGLE_DRIVE_API_KEY=
GOOGLE_SHEETS_API_KEY=
GMAIL_CLIENT_ID=
GMAIL_CLIENT_SECRET=

# OpenAI
OPENAI_API_KEY=

# Gemini
GEMINI_API_KEY=

# Meta Business
META_APP_ID=
META_APP_SECRET=
META_ACCESS_TOKEN=

# Email (IMAP/SMTP)
EMAIL_USER=
EMAIL_PASSWORD=
EMAIL_IMAP_HOST=
EMAIL_SMTP_HOST=
```

---

## 📄 Documentación por Agente

Cada carpeta de agente contiene:
- `IDENTITY.md`: Propósito y temperamento del agente
- `SOUL.md`: Instrucciones de comportamiento y tono
- Código fuente específico del dominio

---

## 🫂 Comandante

**Juan Pablo**  
Comandante del Ecosistema Antigravity  
*"La organización es la clave de la victoria. La soberanía digital es el fin."*

---

"Hasta la victoria siempre. Venceremos." ✊
