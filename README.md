# Hi, I'm Mihai 👋

Python developer from Romania. I build **complete software systems that people use every day**: from interviewing the people who will use them, through specification, data model and tests, to deployment.

I work with AI coding assistants (Claude Code) as my main tool. I own the specification, architecture, data model, testing and delivery; the AI writes most of the code under my direction. That is how I delivered a production platform for a public institution in five weeks.

### 🏛️ In production
- **PIRUS: internal audit management platform** for a public-sector audit office serving 22 institutions. An auditor writes a finding once; the platform generates all **29 legally required documents** and 3 annual reports. **1,882 automated tests**, five years of history migrated from the legacy software. Built in five weeks. *Private (sensitive data); walkthrough on request.*
- **RoadLimits: pan-European road speed-limit platform.** **86.4 million road segments** across 39 countries (Overture Maps, Parquet, DuckDB), bulk editing, approval workflow, seven roles down to municipality level. Built in five weeks of spare time. *Private; demo on request.*
- **[Notary Scheduler](https://github.com/mmereu97/notary-scheduler)**: the appointment book a notary office works with every day; several workstations, one shared database, full audit log.
- **[DocSearch](https://github.com/mmereu97/Search-index-doc-docx)**: instant full-text search across 180,000+ Word documents (SQLite FTS5, single-writer architecture, 169 tests).

### ⭐ Open-source projects
**Data engineering**
- **[UPS Battery Lakehouse](https://github.com/mmereu97/ups-battery-lakehouse)**: Scrapy + PDF datasheets → Databricks medallion lakehouse; compatibility engine for UPS replacement batteries.
- **[Cinemateca Lakehouse](https://github.com/mmereu97/cinemateca-lakehouse)**: 10,000-film catalogue on Databricks (PySpark, Delta Lake, Unity Catalog, Jobs, AI/BI dashboard).
- **[Cinemateca data pipeline](https://github.com/mmereu97/cinemateca-data-pipeline)**: scraper (Playwright, BeautifulSoup) + Excel → SQLite ETL + FastAPI/React app.

**AI applications**
- **[Cucuvel & Rina](https://github.com/mmereu97/cucuvel-and-rina)**: an AI puppet theatre for children; the characters see, hear and recognise who is speaking, teach lessons and translate into nine languages.
- **[Hunter Protocol](https://github.com/mmereu97/hunter-protocol)**: adaptive psychometric engine; 110 axes, 1,101 questions, a three-wave exam and 74 synergy rules.
- **[Desktop Voice Assistant](https://github.com/mmereu97/desktop-voice-assistant)**: talk to Gemini hands-free; it looks at your screen only when the question needs it.

**Desktop & tools**
- **[BioCore Engine](https://github.com/mmereu97/biocore-engine)**: body-composition tracker that separates fat loss from water noise.
- **[Hardware License Keys](https://github.com/mmereu97/hardware-license-key-system)**: Ed25519-signed, hardware-bound licensing; includes a review of what was wrong with my own v1.
- **[Cube Coach](https://github.com/mmereu97/cube-coach)** · **[Chess Analysis Board](https://github.com/mmereu97/chess-analysis-board)**: Bluetooth smart-cube trainer and in-browser Stockfish analysis.

### 📱 Android apps I use every day (Flutter)
- **[Moon Hunter](https://github.com/mmereu97/moon-hunter-mobile)**: moon-photography planner with a live sky compass, time shift, a year-long opportunity scan and map planning; fully offline.
- **[Monastery Finder](https://github.com/mmereu97/monastery-finder)**: 661 Orthodox monasteries in Romania sorted by distance and direction, with a map and a pilgrimage journal.
- **[Memoratus](https://github.com/mmereu97/memoratus)**: learn texts by heart with a reveal ruler and a first-letter mode.
- **[MemoRec](https://github.com/mmereu97/memo-rec)**: one-tap audio recorder with quality presets and auto-stop.

### 🧭 How I work
- **I learn the domain from the experts.** For the audit platform I knew nothing about auditing, so I set up an interview where Claude questioned an auditor for hours, asking after every topic whether anything was missing. That became the specification.
- **Rules written down, then tested.** Business rules and known pitfalls live in the specification; the tests hold the code to them.
- **Personal data never goes into a repository.** Code and data live side by side, but only the code is published.

### 🛠️ Stack
**Data:** Python · PySpark · Spark SQL · Databricks · Delta Lake · DuckDB · Parquet · pandas · Scrapy · Playwright
**Back end & databases:** FastAPI · SQLite (FTS5) · PostgreSQL · MySQL · Alembic · pytest
**Front end & desktop:** React · PySide6 / PyQt · Three.js · Leaflet
**Mobile:** Flutter · Dart · Android · flutter_map (OpenStreetMap) · GPS & compass sensors · audio recording · local notifications
**AI & audio:** Google Gemini (multimodal) · SpeechBrain · Silero VAD · Edge TTS
**Ops:** Docker · Linux · Caddy · NAS · VPN (Tailscale, WireGuard)

📫 [LinkedIn](https://www.linkedin.com/in/mihai-mereu-software-developer) · mihaimereu97@gmail.com
