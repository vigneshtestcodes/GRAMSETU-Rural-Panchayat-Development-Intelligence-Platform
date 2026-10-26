# GRAMSETU (ग्रामसेतु)

### A Rural Panchayat Development Intelligence Platform
> **BHARATBUILD 2026 · PHASE 3 IDEA PRESENTATION**  
> **Team Viksit Bharat** · *One Panchayat. Local Data. 17 SDGs. Measurable Development.*

[![GitHub Repo](https://img.shields.io/badge/GitHub-Team--Viksit--Bharat%2Fgramsetu-181717?logo=github&style=for-the-badge)](https://github.com/Team-Viksit-Bharat/gramsetu)
[![GitLab Mirror](https://img.shields.io/badge/GitLab-Mirror-FC6D26?logo=gitlab&style=for-the-badge)](https://gitlab.com/Team-Viksit-Bharat/gramsetu)
[![Build & Tests](https://img.shields.io/badge/Tests-19%2F19%20Passing-brightgreen?style=for-the-badge&logo=pytest)](https://github.com/Team-Viksit-Bharat/gramsetu/actions)
[![Python Version](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-blue?style=for-the-badge&logo=python)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## 🌐 Public Repository Links

- **Primary GitHub Repository**: [https://github.com/Team-Viksit-Bharat/gramsetu](https://github.com/Team-Viksit-Bharat/gramsetu)
- **GitLab Mirror**: [https://gitlab.com/Team-Viksit-Bharat/gramsetu](https://gitlab.com/Team-Viksit-Bharat/gramsetu)
- **Interactive OpenAPI / Swagger Documentation**: `http://localhost:8000/docs`

---

## 🎯 The Central Mission

Connecting infrastructure, citizens, Panchayat development, and sustainability into a **single, coherent intelligence layer for rural India**.

```
Local Data  ──────►  Decision  ──────►  Action  ──────►  Impact
```

Rural Panchayats are not short of data, reports, or development schemes. What is missing is the **connective tissue** — a system that links a reported problem to a prioritised decision, a funded project, and a verifiable outcome. Today, these pieces exist in silos:
- Problems get reported informally or politically without structured scoring.
- Infrastructure issues are tracked separately from development goals (a leaking water pipe is treated as a plumbing fix rather than a **Water SDG 6 data point**).
- Project budgets and outcomes live in isolated registers.
- Citizens who report problems have no visibility into assignments, resolution quality, or development impact.

**GRAMSETU closes this gap.**

---

## 🏛️ Platform Modules

1. **PAI-Aligned Report Card**: National benchmark view assessing administrative rigor, fiscal management, service delivery, and digital governance.
2. **LSDG Scorecard**: Real-time tracking across all 9 Local Sustainable Development Goal themes localized by the Ministry of Panchayati Raj (MoPR).
3. **Infrastructure Monitoring**: Water, Roads, Electricity, Transport, and Facilities tracked by operational status, condition, and maintenance urgency.
4. **Citizen Services (Closed-Loop)**: `Report` → `Verify` → `Prioritize` → `Assign` → `Resolve` → `Confirm` → `Measure`.
5. **Project Management**: Budgets, expenditures, physical progress %, and beneficiaries linked directly to SDG targets.
6. **Sustainability Centre**: Environmental tracking for water recharge potential, solid waste segregation %, solar energy capacity (kW), and Gram Sabha participation.
7. **AI Development Advisor**: Identifies persistent gaps, recommends targeted GPDP interventions, projects score gains, and estimates costs with mandatory human validation.

---

## ⚡ Core Innovation: Multi-Factor Priority Engine

What should a Panchayat solve first? GRAMSETU answers this with an objective, 5-dimensional mathematical scoring algorithm:

$$\text{Priority Score} = \left(\frac{0.25 \cdot S + 0.20 \cdot P + 0.20 \cdot U + 0.20 \cdot C + 0.15 \cdot G}{5.0}\right) \times 100$$

Where every input is evaluated on a calibrated 1 to 5 scale:
1. **Severity ($S$, 25%)**: Extent of physical damage or service interruption.
2. **People Affected ($P$, 20%)**: Number of citizens directly impacted.
3. **Urgency ($U$, 20%)**: Rate at which conditions deteriorate if unaddressed.
4. **Infrastructure Criticality ($C$, 20%)**: Essential lifeline (drinking water, primary road) vs auxiliary amenity.
5. **LSDG Gap ($G$, 15%)**: Weight of the identified gap in local development themes.

### Priority Ranking Output

| Rank | Issue Name | Category | Priority Score | Tier |
|:---:|---|:---:|:---:|:---:|
| **#01** | **Water Leakage (Public Main Line)** | Water | **97.0 / 100** | **HIGH** |
| **#02** | **Streetlight Failure (Main Road)** | Electricity | **84.0 / 100** | **MEDIUM-HIGH** |
| **#03** | **Waste Collection Gap (Ward 4)** | Waste | **70.0 / 100** | **MEDIUM** |
| **#04** | **Culvert Masonry Drainage Damage** | Roads | **64.0 / 100** | **MEDIUM** |

*Note: Platform prioritization informs decision-makers. Human validation by Panchayat leadership is required prior to fund allocation.*

---

## 🔄 Closed-Loop Citizen Journey

Abstract systems become real through stories. GRAMSETU tracks each issue from discovery to development outcome:

```
1. Report     ──► Citizen snaps photo of broken public water line with Ward GPS.
2. Verify     ──► Panchayat Official validates report authenticity.
3. Prioritize ──► Priority Engine ranks ticket #01 in the Panchayat Action Hub.
4. Assign     ──► Maintenance Crew receives structured work order with deadline.
5. Resolve    ──► Field Crew completes pipe repair and submits completion notes.
6. Confirm    ──► Reporting citizen validates work quality on-site.
7. Measure    ──► LSDG Theme 4 (Water-Sufficient) & SDG 6 indicators update automatically.
```

---

## 🌉 The LSDG $\to$ UN SDG Bridge

GRAMSETU maps all 9 Ministry of Panchayati Raj (MoPR) themes directly to the 17 UN Sustainable Development Goals:

```
┌───────────────────────────────────────────────┐
│              LOCAL PANCHAYAT DATA             │
│   (Citizen Reports · Asset Registers · GPDP)  │
└───────────────────────┬───────────────────────┘
                        ▼
┌───────────────────────────────────────────────┐
│                9 LSDG THEMES                  │
│  LSDG-01: Poverty Free & Enhanced Livelihoods │
│  LSDG-02: Healthy Village                     │
│  LSDG-03: Child-Friendly Village              │
│  LSDG-04: Water-Sufficient Village            │
│  LSDG-05: Clean & Green Village               │
│  LSDG-06: Self-Sufficient Infrastructure      │
│  LSDG-07: Socially Secured Village            │
│  LSDG-08: Good Governance Village             │
│  LSDG-09: Engendered Development              │
└───────────────────────┬───────────────────────┘
                        ▼
┌───────────────────────────────────────────────┐
│                 17 UN SDGS                    │
│    (Global Framework for Sustainable Future)  │
└───────────────────────────────────────────────┘
```

---

## 👥 Target Users & Tailored Workflows

- **Panchayat Officials (Plan · Prioritize · Monitor)**: Unified dashboard with PAI scorecard, priority ranking, and crew assignment tools.
- **Citizens (Report · Track · Participate)**: Mobile-ready geotagged issue reporting, live status tracker, and resolution confirmation.
- **Field Teams (Verify · Execute · Update)**: Field repair task roster with location details and on-ground completion submission.
- **Development Teams (Analyse · Measure · Improve)**: Aggregated analytics across LSDG themes, SDG progress, and public expenditure auditing.

---

## 📂 Repository Structure

```
gramsetu/
├── .github/
│   └── workflows/
│       └── ci.yml               # GitHub Actions CI workflow (Python 3.10-3.12)
├── data/
│   ├── sample_panchayat_data.json # Rich baseline dataset for Sundarpur GP, Varanasi
│   └── lsdg_themes.json         # 9 LSDG Themes & 17 UN SDGs definitions
├── docs/
│   ├── ARCHITECTURE.md          # Full architectural blueprint & Low-code strategy
│   ├── PRIORITY_ENGINE.md       # Multi-factor mathematical scoring specification
│   ├── LSDG_FRAMEWORK.md        # Comprehensive 9 LSDG themes indicator mapping
│   └── API_SPEC.md              # REST API endpoint reference
├── src/
│   └── gramsetu/
│       ├── config.py            # Global configuration & Priority Engine weights
│       ├── database.py          # SQLite persistence & automatic data seeding
│       ├── main.py              # FastAPI server assembly & Static UI routing
│       ├── api/                 # REST API endpoints (Issues, Projects, Scorecards, Advisor)
│       ├── core/                # Priority Engine, LSDG Mapper, PAI Engine, AI Advisor
│       ├── models/              # Pydantic schemas & Domain enums
│       └── web/
│           └── static/          # Single Page Application (HTML5, Tailwind, Chart.js)
├── tests/
│   ├── test_priority_engine.py  # Unit tests for scoring, weights & ranking
│   ├── test_lsdg_mapping.py     # Unit tests for LSDG to SDG bridge
│   ├── test_pai_index.py        # Unit tests for PAI benchmark calculations
│   ├── test_ai_advisor.py       # Unit tests for AI gap detection & proposals
│   ├── test_api_issues.py       # Integration tests for citizen closed-loop lifecycle
│   └── test_api_projects.py     # Integration tests for development projects
├── scripts/
│   ├── run_server.py            # Local development & production launcher
│   └── seed_db.py               # Database reset & seeding script
├── pyproject.toml               # Python packaging configuration
├── requirements.txt             # Production & test dependencies
├── LICENSE                      # MIT Open Source License
└── README.md                    # Platform documentation
```

---

## 🚀 Quickstart & Setup Guide

### 1. Prerequisites
- **Python 3.10+** (Tested on Python 3.10, 3.11, and 3.12)
- **Git** (optional, for version control)

### 2. Clone or Initialize Repository

```bash
git clone https://github.com/Team-Viksit-Bharat/gramsetu.git
cd gramsetu
```

*(If setting up a fresh local repository to push to your own GitHub/GitLab account:)*
```bash
git init
git add .
git commit -m "feat: initial release of GRAMSETU Rural Intelligence Platform"
git branch -M main
git remote add origin https://github.com/<your-username>/gramsetu.git
git push -u origin main
```

### 3. Install Dependencies

```bash
# Optional: Create and activate virtual environment
python -m venv venv
# On Windows:
.\venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

# Install requirements
pip install -r requirements.txt
```

### 4. Seed the Database

The system comes preloaded with realistic pilot data for **Sundarpur Gram Panchayat (Varanasi, UP)**:

```bash
python scripts/seed_db.py
```

### 5. Launch the Platform

```bash
python scripts/run_server.py
```

Now open your browser:
- 💻 **Interactive Web Application**: [http://localhost:8000](http://localhost:8000)
- 📖 **Interactive OpenAPI (Swagger) Documentation**: [http://localhost:8000/docs](http://localhost:8000/docs)
- 📑 **Alternative Redoc Documentation**: [http://localhost:8000/redoc](http://localhost:8000/redoc)

---

## 🧪 Running Test Cases

The test suite covers the Priority Engine math, LSDG/SDG mapping, PAI calculations, AI advisor recommendations, and full closed-loop issue lifecycle workflows:

```bash
pytest -v
```

Expected output:
```text
tests/test_ai_advisor.py::test_advisor_generates_recommendations PASSED
tests/test_api_issues.py::test_get_panchayat_meta PASSED
tests/test_api_issues.py::test_health_check PASSED
tests/test_api_issues.py::test_get_issues_ranking PASSED
tests/test_api_issues.py::test_closed_loop_issue_lifecycle PASSED
tests/test_api_projects.py::test_get_projects PASSED
tests/test_api_projects.py::test_create_project PASSED
tests/test_api_projects.py::test_get_scorecards PASSED
tests/test_lsdg_mapping.py::test_water_category_mapping PASSED
tests/test_lsdg_mapping.py::test_electricity_mapping PASSED
tests/test_lsdg_mapping.py::test_roads_mapping PASSED
tests/test_lsdg_mapping.py::test_theme_status_evaluations PASSED
tests/test_pai_index.py::test_tier_determinations PASSED
tests/test_pai_index.py::test_overall_calculation PASSED
tests/test_priority_engine.py::test_max_score PASSED
tests/test_priority_engine.py::test_min_score PASSED
tests/test_priority_engine.py::test_sample_water_leakage_score PASSED
tests/test_priority_engine.py::test_clamping_behavior PASSED
tests/test_priority_engine.py::test_rank_issues_ordering PASSED
============================= 19 passed in 0.34s ==============================
```

---

## 📊 Sample Panchayat Snapshot (Sundarpur GP)

- **Local Body**: Sundarpur Gram Panchayat (LGD Code: `134289`)
- **Block & District**: Kalyanpur Block, Varanasi District, Uttar Pradesh
- **Population**: 4,820 residents across 840 households in 6 Wards
- **PAI Score**: **76.4 / 100** (Tier: *Front Runner*, 84.2nd National Percentile)
- **Key Infrastructure**: 
  - Jal Jeevan 100 kL Overhead Tank (Ward 2)
  - Kalyanpur Link PMGSY Pucca Road (Ward 1)
  - Village Square Solar High-Mast Light (Ward 3)
  - Primary Health Sub-Centre (Ward 4)
  - Anganwadi Early Child Care Centre (Ward 5)
- **Active GPDP Projects**:
  1. Community Rainwater Harvesting & Amrit Sarovar Pond Rejuvenation (₹8.5 L)
  2. Decentralized Greywater Soak Pit Grid Phase 2 (₹4.8 L)
  3. Solar Micro-Grid for Gram Sachivalaya & PHC (₹6.2 L)
  4. Anganwadi Smart Learning & Nutrition Hub (₹2.5 L)

---

## ⚖️ License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full details.

---

## 🇮🇳 Acknowledgements & Vision

Developed for **BHARATBUILD 2026** by **Team Viksit Bharat**.  
Aligned with the **Ministry of Panchayati Raj (MoPR)**, **e-GramSwaraj**, and the **United Nations Sustainable Development Goals (UN SDGs)**.

*Innovating for Bharat — one Panchayat at a time.*
