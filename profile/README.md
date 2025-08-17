# Memori AI

<p align="center">
  <img src="https://ghost.memori.ai/content/images/2024/03/AISURU_COLOR.svg" alt="Memori AI Logo" width="200"/>
</p>

<p align="center">
  <strong>AI for all. Conversational AI that grows with its creator.</strong>
</p>

<p align="center">
  <a href="https://www.memori.ai">Website</a> •
  <a href="https://docs.aisuru.com">Documentation</a> •
  <a href="https://www.aisuru.com">AIsuru Platform</a>
</p>

## 🚀 Overview

Memori AI è una startup italiana specializzata nello sviluppo di tecnologie di intelligenza artificiale conversazionale. La nostra missione è portare la dimensione umana al centro della creazione di intelligenza artificiale, con l'obiettivo di migliorare la vita delle persone.

Adottiamo un approccio conversazionale end-to-end: le nostre Intelligenze Artificiali Conversazionali (CAI) crescono con il loro creatore attraverso semplici conversazioni. Chiamiamo questo approccio "extreme no-code": il creatore non ha bisogno di conoscere codice di sviluppo software o utilizzare interfacce grafiche complesse.

## 🧩 Librerie principali

Memori offre tre librerie principali per l'integrazione frontend:

### 1. [memori-api-client](https://github.com/memori-ai/memori-api-client)

Client TypeScript per interagire direttamente con le API Memori.

```bash
# npm
npm install @memori.ai/memori-api-client
# yarn
yarn add @memori.ai/memori-api-client
```

**Caratteristiche:**
- Gestione completa di autenticazione e sessioni
- Interazione con le API Engine e Backend
- Supporto per eventi di dialogo e gestione del contesto
- Completamente tipizzato con TypeScript

### 2. [memori-webcomponent](https://github.com/memori-ai/memori-webcomponent)

Componente web standard utilizzabile in qualsiasi pagina HTML.

```html
<!-- Installazione via CDN -->
<script type="module" src="https://cdn.jsdelivr.net/npm/@memori.ai/memori-webcomponent/dist/memori-webcomponent.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@memori.ai/memori-react/dist/styles.min.css"/>
```

```bash
# npm
npm install @memori.ai/memori-webcomponent
# yarn
yarn add @memori.ai/memori-webcomponent
```

**Caratteristiche:**
- Utilizzo immediato in HTML puro
- Nessuna dipendenza da framework specifici
- Configurazione tramite attributi HTML
- Gestione automatica del ciclo di vita del componente

### 3. [memori-react](https://github.com/memori-ai/memori-react)

Componente React dedicato per una maggiore flessibilità.

```bash
# npm
npm install @memori.ai/memori-react
# yarn
yarn add @memori.ai/memori-react
```

**Caratteristiche:**
- Integrazione nativa con React
- Supporto TypeScript completo
- Layout personalizzabili
- Sistema di eventi avanzato
- Possibilità di override dei componenti
- Gestione stato integrata

## 🎨 Layout disponibili

Il componente React offre diversi layout predefiniti:

- **FULLPAGE**: Esperienza a schermo intero, ideale per pagine dedicate
- **WEBSITE_ASSISTANT**: Assistente fluttuante, perfetto per l'integrazione in siti web
- **CHAT**: Interfaccia chat focalizzata sui messaggi
- **ZOOMED_FULL_BODY**: Layout a pagina intera con avatar ingrandito
- **HIDDEN_CHAT**: Chat laterale, nascosta fino all'interazione dell'utente
- **TOTEM**: Layout adatto per totem digitali

Inoltre, è possibile creare layout completamente personalizzati.

## 🔌 Architettura API

L'API Memori consiste in due componenti principali:

1. **API Engine** ([Swagger](https://engine.memori.ai/swagger/index.html))
   - Gestisce sessioni e dialoghi
   - Gestisce funzionalità NLP
   - Elabora funzionalità conversazionali

2. **API Backend** ([Swagger](https://backend.memori.ai/memoriai/swagger/index.html))
   - Gestisce utenti e asset
   - Gestisce notifiche
   - Controlla amministrazione sistema

## 📚 Esempi e risorse

- [Esempi di integrazione](https://github.com/memori-ai/examples)
- [Layout personalizzato di esempio](https://github.com/andrepat0/memory-media-layout)
- [Demo live del layout personalizzato](https://andrepat0.github.io/memory-media-layout/)

## 🛠️ Prodotti

- **AIsuru Platform**: Piattaforma SaaS per la creazione e gestione di agenti conversazionali
- **AI Academy**: Corsi di formazione per l'utilizzo di AI conversazionale

## 🤝 Supporto

- [Documentazione completa](https://docs.aisuru.com)
- [API Reference](https://docs.aisuru.com/api)
- [Agente di supporto Manuela](https://www.aisuru.com/it/memoridev/Manuela/54ac7607-6905-4a0d-9f50-5ec178e846a3)
- [Meta Prompt Engineer](https://www.aisuru.com/en/dpezzettone/Meta%20Prompt%20Engineer)

## 📧 Contatti

- Email di supporto: ccare@memori.ai
- Email generale: info@memori.ai
- Demo e consulenza: demo@memori.ai
- Sito web: [www.memori.ai](https://www.memori.ai)
