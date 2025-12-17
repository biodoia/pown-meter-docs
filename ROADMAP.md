# Roadmap - POWN METER

## Status: ⏸️ PROGETTO SOSPESO

**Data sospensione**: Dicembre 2024
**Fase corrente**: Pianificazione completata
**Prossimo step quando ripreso**: Setup ambiente e Facebook Developer App

---

## Legenda
- ✅ Completato
- ⏸️ Sospeso
- 📋 Pianificato
- 💡 Idea Futura

---

## Fase 0: Pianificazione ✅ COMPLETATA

### Documentazione Tecnica
- ✅ Architettura sistema e diagrammi
- ✅ Schema database PostgreSQL completo
- ✅ Design API REST (50+ endpoints)
- ✅ Design system punk/cyberpunk
- ✅ Sistema gamification (7 livelli, 8+ achievements)
- ✅ Documentazione Facebook OAuth completa

### Repository & Tools
- ✅ Repository privato (codice sorgente)
- ✅ Repository pubblico (docs, wiki, roadmap)
- ✅ Script test visibilità profilo Facebook
- ✅ Template issue per feature request e bug report
- ✅ Wiki utente (Quick Start, FAQ, Gamification)

### Test Iniziali
- ✅ Test visibilità profilo target
  - **Risultato**: Post NON pubblici
  - **Conclusione**: OAuth obbligatorio (scraping non funziona)
  - **Action**: Flow OAuth user-friendly già documentato

---

## Fase 1: Setup Ambiente ⏸️

### Infrastruttura
- 📋 Setup ambiente Python (venv/poetry)
- 📋 Docker Compose per sviluppo locale
- 📋 Configurazione CI/CD

### Facebook Developer
- 📋 Creare Facebook App
- 📋 Configurare OAuth settings
- 📋 Ottenere App ID e Secret
- 📋 Preparare per App Review

---

## Fase 2: Backend Core ⏸️

### API & Database
- 📋 Inizializzare FastAPI project
- 📋 SQLAlchemy + Alembic migrations
- 📋 Implementare modelli database
- 📋 Sistema autenticazione JWT
- 📋 CRUD completo (users, specimens, votes)

### Facebook Integration
- 📋 OAuth flow completo
- 📋 Token storage criptato
- 📋 Token refresh automatico
- 📋 Graph API per fetch posts

---

## Fase 3: Intelligenza ⏸️

### OCR & Analisi
- 📋 Integrazione Tesseract OCR
- 📋 Preprocessing immagini
- 📋 Riconoscimento layout chat
- 📋 AI analysis (Claude/OpenAI)
- 📋 Sistema scoring automatico
- 📋 Categorizzazione (8 categorie)

### Monitoring
- 📋 Setup Celery + Redis
- 📋 Job periodico monitoring
- 📋 Detection screenshot vs altre immagini
- 📋 Deduplicazione hash-based

---

## Fase 4: Gamification ⏸️

### Sistema Punti & Livelli
- 📋 Calcolo punti con moltiplicatori
- 📋 7 livelli di progressione
- 📋 Titoli personalizzati

### Achievements
- 📋 Engine achievements
- 📋 8+ badge sbloccabili
- 📋 Notifiche punk allo sblocco

### Notifiche
- 📋 Notifiche in-app demenziali
- 📋 Email notifiche (opzionale)

---

## Fase 5: Frontend ⏸️

### Design System
- 📋 CSS punk/cyberpunk custom
- 📋 Effetti glitch, scanlines, neon
- 📋 Componenti UI reusabili

### Pagine
- 📋 Landing con "Connetti Facebook"
- 📋 Homepage / Feed
- 📋 Galleria screenshot
- 📋 Statistiche personali + assurde
- 📋 Hall of Shame
- 📋 Profilo utente
- 📋 Settings

### Interazione
- 📋 Sistema voto (fire, skull, vomit, crown)
- 📋 Social sharing
- 📋 Template grafici punk

---

## Fase 6: Polish & Launch ⏸️

- 📋 Testing completo
- 📋 Ottimizzazione performance
- 📋 Setup hosting produzione
- 📋 CDN per assets
- 📋 Monitoring & logging
- 📋 Facebook App Review
- 📋 Beta testing con utente target
- 📋 Launch! 🚀

---

## Backlog 💡

Idee per il futuro (non prioritarie):

- 💡 **PWA / App Mobile** - Versione mobile nativa
- 💡 **Bot Telegram** - Notifiche via Telegram
- 💡 **API Pubblica** - Per integrazioni terze parti
- 💡 **Estensione Browser** - Cattura diretta da Facebook
- 💡 **Widget Embeddabile** - Da mettere sul proprio sito
- 💡 **Temi Alternativi** - Vaporwave, retro, etc.
- 💡 **Multilingua** - Supporto altre lingue
- 💡 **Statistiche Avanzate** - Grafici interattivi
- 💡 **Leaderboard Globale** - Classifica tra utenti pubblici
- 💡 **Modalità Competitiva** - Sfide settimanali

---

## Come Contribuire alle Idee

Hai un'idea? [Apri una Feature Request!](../../issues/new?template=feature_request.md)

Le feature più votate dalla community salgono in priorità.

---

## Per Riprendere lo Sviluppo

1. Leggere documentazione in `docs/`
2. Creare Facebook Developer App
3. Setup ambiente locale
4. Iniziare da Fase 1

---

*Ultimo aggiornamento: Dicembre 2024*
