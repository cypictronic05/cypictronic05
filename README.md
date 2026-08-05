<div align="center">

# 👋 ¡Hola! Soy Simón Vitriago

### Ingeniero Electricista · Desarrollador Full Stack · Automatización · IoT · IA aplicada

Construyo soluciones que conectan **software, automatización, electrónica, datos e inteligencia artificial** para resolver problemas reales.

[![GitHub](https://img.shields.io/badge/GitHub-cypictronic05-181717?style=for-the-badge&logo=github)](https://github.com/cypictronic05)
[![Website](https://img.shields.io/badge/Cocuyotec-Sitio_web-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cocuyotec.com)
[![YouTube](https://img.shields.io/badge/YouTube-Cypictronic-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@cypictronic)

![Profile views](https://komarev.com/ghpvc/?username=cypictronic05&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/cypictronic05?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/cypictronic05?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge)

</div>

---

## 🚀 Sobre mí

Soy **ingeniero electricista y desarrollador de software**, enfocado en crear productos digitales completos: desde la idea y la arquitectura hasta el despliegue, la automatización y la integración con sistemas físicos.

- 🌐 Desarrollo aplicaciones web modernas y responsivas.
- ⚙️ Automatizo procesos con **n8n, APIs, webhooks y bases de datos**.
- 🏭 Integro software con **PLC, SCADA, Arduino, sensores e IoT**.
- 🤖 Aplico inteligencia artificial a educación, contenido y productividad.
- 📊 Diseño dashboards, sistemas administrativos y herramientas de análisis.
- 🚀 Despliego proyectos en **Vercel, VPS, Docker, PM2 y servicios cloud**.
- 🎓 Comparto conocimientos sobre programación, electrónica e IA.

---

## 🧭 Ecosistema de proyectos

```mermaid
flowchart TB
    SV["👨‍💻 Simón Vitriago<br/>Ingeniería + Software + Automatización"]

    SV --> IND["🏭 Industria e IoT"]
    SV --> WEB["🌐 Productos Web"]
    SV --> AUTO["⚙️ Automatización"]
    SV --> EDU["🎓 Educación"]
    SV --> NEG["💼 Negocios Digitales"]
    SV --> IA["🤖 IA y Contenido"]

    IND --> SCADA["Sorter SCADA<br/>PLC Siemens + Node.js + PostgreSQL"]
    IND --> ARDUINO["Control Arduino Web<br/>SerialPort + Interfaces Web"]
    IND --> SOCKET["Socket Server<br/>Comunicación en tiempo real"]

    WEB --> COCUYO["Cocuyotec SPA<br/>Agencia tecnológica"]
    WEB --> PORTFOLIO["Portafolios profesionales"]
    WEB --> ECOMMERCE["Tiendas y catálogos"]
    WEB --> CLIENTES["Webs para clientes y marcas"]

    AUTO --> N8N["Flujos n8n"]
    AUTO --> WHATSAPP["WhatsApp Business"]
    AUTO --> APIS["APIs + Webhooks"]
    AUTO --> DATA["Firebase / PostgreSQL / Supabase"]

    EDU --> SOPHIA["Soph-IA<br/>Tutora virtual"]
    EDU --> ALURA["Challenges Alura ONE"]
    EDU --> JUEGOS["Juegos educativos"]
    EDU --> CALC["Calculadoras y utilidades"]

    NEG --> REMESAS["Sistema de remesas"]
    NEG --> ORBI["ORBI Ecosystem"]
    NEG --> CAPITAL["WOS Capital Humano"]
    NEG --> LIBROS["Plataformas editoriales"]

    IA --> VIDEOS["Contenido audiovisual con IA"]
    IA --> MUSICA["Música generativa"]
    IA --> NEWS["Contenido y noticias"]
```

---

## ⭐ Proyectos destacados

### 🏭 Sorter SCADA — Supervisión industrial en tiempo real

Sistema SCADA web diseñado para monitorear y analizar una línea de clasificación logística.

```mermaid
flowchart LR
    PLC["PLC Siemens S7"] --> API["Backend Node.js"]
    API --> WS["WebSocket"]
    API --> DB["PostgreSQL"]
    WS --> UI["Dashboard SCADA"]
    DB --> KPI["KPIs y reportes"]
    UI --> OP["Operadores"]
    KPI --> MG["Gestión"]
```

**Características principales**

- Lectura de señales del PLC y simulación en modo mock.
- Monitoreo de rampas, ocupación, fallas y pausas.
- Producción por hora y acumulados por turno.
- Cálculo de KPIs desde el backend.
- Persistencia histórica en PostgreSQL.
- Dashboard operativo y panel gerencial.
- Arquitectura preparada para Siemens S7, PLCSIM y entorno industrial.

**Tecnologías:** Node.js · Express · WebSocket · PostgreSQL · Siemens S7 · TIA Portal · PLCSIM · Factory I/O

---

### ✨ Cocuyotec SPA — Agencia tecnológica

Ecosistema digital para ofrecer soluciones de desarrollo y automatización.

```mermaid
mindmap
  root((Cocuyotec))
    Desarrollo Web
      Landing pages
      Sitios corporativos
      Plataformas
      E-commerce
    Aplicaciones
      Android
      iOS
      PWA
    Automatización
      n8n
      APIs
      WhatsApp
      Integraciones
    Contenido
      Edición de video
      IA generativa
      Branding
```

🌐 **Sitio:** [cocuyotec.com](https://cocuyotec.com)  
📁 **Repositorio:** [cypictronic05/cocuyotec](https://github.com/cypictronic05/cocuyotec)

---

### 🤖 Soph-IA — Tutora virtual educativa

Proyecto educativo que combina una interfaz web con herramientas interactivas para apoyar el aprendizaje.

```mermaid
flowchart LR
    STUDENT["👩‍🎓 Estudiante"] --> CHAT["Interfaz educativa"]
    CHAT --> LOGIC["Motor pedagógico"]
    LOGIC --> MATH["MathJax"]
    LOGIC --> CONTENT["Ejercicios y explicaciones"]
    LOGIC --> FEEDBACK["Retroalimentación"]
```

**Enfoque:** matemáticas, aprendizaje guiado, ejercicios interactivos y apoyo mediante IA.

Repositorios relacionados:

- [tutora-virtual-sophia-privacy-policy](https://github.com/cypictronic05/tutora-virtual-sophia-privacy-policy)
- [web-ingles-sophia-unit7](https://github.com/cypictronic05/web-ingles-sophia-unit7)
- [horario-sophia](https://github.com/cypictronic05/horario-sophia)

---

### 🔌 Control Arduino desde la web

Aplicación para comunicar una interfaz web con Arduino y dispositivos electrónicos.

```mermaid
sequenceDiagram
    participant U as Usuario
    participant W as Interfaz Web
    participant N as Node.js
    participant S as SerialPort
    participant A as Arduino

    U->>W: Ejecuta una acción
    W->>N: Envía comando
    N->>S: Escribe en puerto serial
    S->>A: Transmite instrucción
    A-->>S: Devuelve estado
    S-->>N: Lectura del dispositivo
    N-->>W: Actualiza interfaz
```

📁 [control-arduino-web](https://github.com/cypictronic05/control-arduino-web)  
📁 [node-arduino-serialport](https://github.com/cypictronic05/node-arduino-serialport)  
📁 [socket-server](https://github.com/cypictronic05/socket-server)

---

### 💸 Plataforma de operaciones y remesas

Sistema orientado a administrar solicitudes, tasas, cálculos, comprobantes y operaciones internacionales.

```mermaid
flowchart LR
    CLIENT["Cliente"] --> WA["WhatsApp Business"]
    WA --> N8N["Automatización n8n"]
    N8N --> RATES["Tasas"]
    N8N --> DB["Firebase / Base de datos"]
    N8N --> OPS["Gestión de operaciones"]
    OPS --> PAY["Pago destino"]
    PAY --> RECEIPT["Comprobante"]
    RECEIPT --> RECORD["Registro administrativo"]
```

**Componentes trabajados:** automatización de atención, cálculo de operaciones, gestión por país, validación de comprobantes y registro administrativo.

---

### 🌐 ORBI Ecosystem

Plataforma web que presenta un ecosistema de soluciones tecnológicas y servicios digitales.

🔗 [orbiecosystem.vercel.app](https://orbiecosystem.vercel.app/)

---

### 👥 WOS Capital Humano

Plataforma corporativa para reclutamiento y selección de personal, orientada especialmente a minería y otros sectores productivos.

```mermaid
flowchart LR
    COMPANY["Empresa"] --> REQUEST["Solicitud de personal"]
    REQUEST --> FILTER["Evaluación de perfiles"]
    FILTER --> CANDIDATES["Candidatos"]
    CANDIDATES --> INTERVIEW["Entrevista"]
    INTERVIEW --> SHORTLIST["Selección"]
    SHORTLIST --> HIRE["Contratación"]
```

🔗 [woscapitalhumano.cl](https://woscapitalhumano.cl)

---

### 📚 Salvador Escritor

Plataforma web de presentación y comercialización de obras editoriales.

📁 [salvador-escritor](https://github.com/cypictronic05/salvador-escritor)

---

## 🧩 Más proyectos públicos

| Proyecto | Descripción |
|---|---|
| [challenge-portafolio-2025](https://github.com/cypictronic05/challenge-portafolio-2025) | Portafolio profesional moderno |
| [personal-portfolio-2024](https://github.com/cypictronic05/personal-portfolio-2024) | Portafolio personal de desarrollador |
| [challenge-aluraGeek](https://github.com/cypictronic05/challenge-aluraGeek) | Catálogo tipo e-commerce |
| [challenge-encriptador-alura](https://github.com/cypictronic05/challenge-encriptador-alura) | Encriptador y desencriptador de texto |
| [Alura-One-Backend1](https://github.com/cypictronic05/Alura-One-Backend1) | Prácticas y retos backend |
| [alura-temporizador](https://github.com/cypictronic05/alura-temporizador) | Temporizador interactivo |
| [alura-midi](https://github.com/cypictronic05/alura-midi) | Instrumento musical web |
| [juego-secreto](https://github.com/cypictronic05/juego-secreto) | Juego de lógica y números |
| [tren-movimiento](https://github.com/cypictronic05/tren-movimiento) | Animación y movimiento web |
| [anatomy](https://github.com/cypictronic05/anatomy) | Proyecto visual y educativo |
| [capitales-paises](https://github.com/cypictronic05/capitales-paises) | Aplicación educativa de geografía |
| [digito-verificador](https://github.com/cypictronic05/digito-verificador) | Utilidad para validación de datos |
| [presupuesto](https://github.com/cypictronic05/presupuesto) | Herramienta de cálculo de presupuestos |
| [Artesania-Sergio-Rojas](https://github.com/cypictronic05/Artesania-Sergio-Rojas) | Web comercial para artesanía |
| [sergiorojascreaciones](https://github.com/cypictronic05/sergiorojascreaciones) | Sitio de marca y catálogo |
| [mercado-pago-documentacion](https://github.com/cypictronic05/mercado-pago-documentacion) | Integración y documentación de pagos |

---

## 🛠️ Tecnologías

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite,astro,bootstrap,tailwind" />
</p>

### Backend y datos

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,postgres,supabase,firebase,mongodb" />
</p>

### DevOps y despliegue

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker,vercel,linux,nginx" />
</p>

### Electrónica, automatización e industria

<p>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

- Siemens PLC / TIA Portal
- PLCSIM y Factory I/O
- Comunicación serial
- WebSocket y sistemas en tiempo real
- SCADA web
- n8n, APIs REST y webhooks
- WhatsApp Business y automatización de procesos

---

## 🏗️ Cómo construyo soluciones

```mermaid
flowchart LR
    IDEA["💡 Problema"] --> ANALYSIS["🔎 Análisis"]
    ANALYSIS --> UX["🎨 UX/UI"]
    UX --> ARCH["🏗️ Arquitectura"]
    ARCH --> DEV["💻 Desarrollo"]
    DEV --> TEST["🧪 Pruebas"]
    TEST --> DEPLOY["🚀 Despliegue"]
    DEPLOY --> DATA["📊 Medición"]
    DATA --> IMPROVE["🔁 Mejora continua"]
    IMPROVE --> ANALYSIS
```

Mi objetivo no es solamente escribir código, sino entregar soluciones **útiles, medibles, mantenibles y preparadas para crecer**.

---

## 📊 Estadísticas de GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=cypictronic05&show_icons=true&theme=tokyonight&hide_border=true&locale=es" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cypictronic05&layout=compact&theme=tokyonight&hide_border=true&locale=es" />

<img src="https://streak-stats.demolab.com?user=cypictronic05&theme=tokyonight&hide_border=true&locale=es" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=cypictronic05&theme=tokyo-night&hide_border=true" />

</div>

---

## 🎯 Actualmente estoy trabajando en

- Sistemas SCADA web e integración con PLC.
- Aplicaciones empresariales con Node.js y PostgreSQL.
- Automatización de atención y operaciones mediante n8n.
- Productos digitales para Cocuyotec SPA.
- Herramientas educativas asistidas por IA.
- Integraciones entre software, electrónica y procesos reales.

---

## 🤝 Colaboraciones

Me interesan proyectos relacionados con:

- Automatización industrial.
- Plataformas web empresariales.
- Inteligencia artificial aplicada.
- Educación tecnológica.
- IoT y electrónica.
- Sistemas administrativos.
- Transformación digital para pequeñas y medianas empresas.

---

<div align="center">

## 📬 Conectemos

**¿Tienes una idea, un proceso que automatizar o un proyecto tecnológico?**

[![GitHub](https://img.shields.io/badge/Explorar_repositorios-181717?style=for-the-badge&logo=github)](https://github.com/cypictronic05?tab=repositories)
[![Cocuyotec](https://img.shields.io/badge/Visitar_Cocuyotec-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cocuyotec.com)
[![YouTube](https://img.shields.io/badge/Ver_canal_de_YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@cypictronic)

### ⚡ Ingeniería que conecta ideas, software y tecnología.

</div>
