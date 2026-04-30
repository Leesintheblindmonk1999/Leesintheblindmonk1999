<div align="center">

### 🌐 Language / Idioma

[🇺🇸 English](#english-version) &nbsp;&nbsp;|&nbsp;&nbsp; [🇦🇷 Español](#versión-en-español)

</div>

---

<a name="english-version"></a>

<div align="center">

# Gonzalo Emir Durante
## Origin Node · Architect of Critical Systems

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   ███████╗ █████╗ ███████╗                                                   ║
║   ██╔════╝██╔══██╗██╔════╝                                                   ║
║   ███████╗███████║███████╗                                                   ║
║   ╚════██║██╔══██║╚════██║                                                   ║
║   ███████║██║  ██║███████║                                                   ║
║   ╚══════╝╚═╝  ╚═╝╚══════╝                                                   ║
║                                                                              ║
║          S Y M B I O T I C   A U T O P R O T E C T I O N   S Y S T E M      ║
║                                                                              ║
║              P R O J E C T   M A N I F O L D   0 . 5 6                      ║
║                                                                              ║
║         "Structural Coherence Auditing for Generative AI"                    ║
║                  κD = 0.56  ·  TAD EX-2026-18792778                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

[![SAS DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19702379.svg)](https://doi.org/10.5281/zenodo.19702379)
[![Omni-Scanner DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19543972.svg)](https://doi.org/10.5281/zenodo.19543972)
[![Core DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19172490.svg)](https://doi.org/10.5281/zenodo.19172490)
[![API Online](https://img.shields.io/badge/SAS_API-online-brightgreen)](https://sas-api.onrender.com)
[![FastAPI](https://img.shields.io/badge/API-FastAPI-009688)](https://sas-api.onrender.com/docs)
[![License: GPL-3.0 + Durante Invariance](https://img.shields.io/badge/License-GPL--3.0%20%2B%20Durante%20Invariance-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![SAS Validation](https://img.shields.io/badge/SAS-98.8%25_accuracy-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/SAS)
[![Precision](https://img.shields.io/badge/Precision-100%25-success)](https://github.com/Leesintheblindmonk1999/SAS)
[![HALOGEN](https://img.shields.io/badge/HALOGEN-156k_pairs-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/Omni_Scanner)
[![OTS](https://img.shields.io/badge/OTS-Bitcoin_Anchored-orange.svg)](https://opentimestamps.org)

**Critical Systems Architect** · **AI Forensic Auditor** · **Open Science**

[🛡️ SAS v1.1.0](#-flagship-sas-v110) · [🔬 Omni-Scanner Core](#-core-engine-omni-scanner-v101) · [🏗️ Research Ecosystem](#-research-ecosystem) · [📚 Publications](https://doi.org/10.5281/zenodo.19702379) · [💼 LinkedIn](https://linkedin.com/in/gonzalo-emir-durante-8178b6277/) · [📧 Contact](mailto:duranteg2@gmail.com)

</div>

---

## ⬡ Research Mission

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  OBJECTIVE:  Structural auditing of LLM outputs via SAS + Omni-Scanner      │
│  APPROACH:   Mathematical invariance, topological comparison, API evidence  │
│  CONSTANT:   κD = 0.56  (Durante Constant — structural coherence threshold) │
│  SAS CORPUS: 2,000 pairs — 1,000 hallucinations + 1,000 clean examples      │
│  SAS RESULT: 98.80% accuracy · 100.00% precision · 97.60% recall           │
│  CORE HALOGEN: 156,215 real pairs · 97.63% precision · 61.81% recall       │
└─────────────────────────────────────────────────────────────────────────────┘
```

The current flagship is **SAS - Symbiotic Autoprotection System v1.1.0**: an open-source FastAPI service for structural hallucination auditing in generative AI outputs.

SAS is powered by the Omni-Scanner / Project Manifold 0.56 research line and uses **κD = 0.56** as the operational threshold for semantic invariance and manifold rupture detection.

---

## 🛡️ Flagship: SAS v1.1.0

<div align="center">

### **[SAS — Symbiotic Autoprotection System](https://github.com/Leesintheblindmonk1999/SAS)**

*Hosted structural hallucination detection API for generative AI outputs.*

**Live API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Interactive docs:** [https://sas-api.onrender.com/docs](https://sas-api.onrender.com/docs)  
**DOI:** [10.5281/zenodo.19702379](https://doi.org/10.5281/zenodo.19702379)

</div>

### What SAS does

SAS evaluates whether a generated response preserves:

- semantic structure;
- logical consistency;
- numerical integrity;
- reference / grounding coherence;
- topic continuity;
- structural alignment with the source or prompt.

It is not a universal factual oracle. It is a **technical evidence layer** for structural coherence auditing and selected high-precision hallucination signals.

### Live public API

```bash
curl https://sas-api.onrender.com/health
```

Example hosted API usage:

```bash
curl -X POST https://sas-api.onrender.com/v1/diff \
  -H "Content-Type: application/json" \
  -H "X-API-Key: sas_xxxxxxxxxxxxxxxxxxxxx" \
  -d '{
    "text_a": "Python is a programming language commonly used for automation and data analysis.",
    "text_b": "A python is a large tropical snake that constricts its prey.",
    "experimental": true
  }'
```

### SAS v1.1.0 Benchmark

```
╔══════════════════════════════════════════════════════════════════╗
║  BENCHMARK: SAS v1.1.0 · 2,000 evaluated text pairs             ║
╠══════════════════════════════════════════════════════════════════╣
║  Hallucination examples :  1,000                                 ║
║  Clean examples         :  1,000                                 ║
║  Accuracy               :  98.80%                                ║
║  Precision              : 100.00%                                ║
║  Recall                 :  97.60%                                ║
║  F1 score               :  98.79%                                ║
║  True Positives         :  976                                   ║
║  False Negatives        :  24                                    ║
║  True Negatives         :  1000                                  ║
║  False Positives        :  0                                     ║
║  Avg ISI hallucination  :  0.072993                              ║
║  Avg ISI clean          :  1.000000                              ║
╚══════════════════════════════════════════════════════════════════╝
```

### Confusion Matrix

| Prediction | Actual hallucination | Actual clean |
|-----------|---------------------:|-------------:|
| Hallucination | TP = 976 | FP = 0 |
| Clean | FN = 24 | TN = 1000 |

### Benchmark Traceability

| Artifact | Value |
|---------|-------|
| Benchmark file | `benchmark_complete_20260429_172647.json` |
| OTS proof | `benchmark_complete_20260429_172647.json.ots` |
| SHA-256 | `0713acbbf50e1a0054f545e5eb68078744f9c5a09d4bc370b5224bb81183a6fe` |
| DOI SAS | `10.5281/zenodo.19702379` |
| Registry | `TAD EX-2026-18792778` |

### SAS Plans

SAS is open source under **GPL-3.0 + Durante Invariance License**. The following plans refer to the hosted API service, not to a relaxation of the source-code license.

| Plan | Usage / Features | Price |
| :--- | :--- | :--- |
| **SAS Free** | 50 requests/day. API key authentication. Ideal for development, testing, and evaluation. | **Free** |
| **SAS Pro** | 10,000 requests/month. No concurrency limit. Priority email support. | **$49 USD/month** or **$490 USD/year** |
| **SAS Enterprise** | Unlimited requests or custom package. Guaranteed SLA 99.9%. Optional on-premise license. 24/7 support. | **Custom quote** — starting at **$499/month** |

📧 **Enterprise / custom plans:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

---

## 🔬 Core Engine: Omni-Scanner v10.1

<div align="center">

### **[Omni-Scanner v10.1 — Structural Hallucination Auditing Engine](https://github.com/Leesintheblindmonk1999/Omni_Scanner)**

*Topological detection of LLM hallucinations via persistent homology, numerical invariance, and domain-specific process thermometers.*

</div>

Omni-Scanner remains the mathematical and forensic core behind the SAS line. It contains the TDA + NIG + v10.1 module pipeline that SAS exposes through an operational API.

### Quick usage

```bash
pip install -r requirements.txt
cd omni-scanner-api
uvicorn app.main:app --reload
# open http://localhost:8000/docs
```

### Audit a text

```bash
curl -X POST http://localhost:8000/v1/audit \
  -H "Content-Type: application/json" \
  -d '{"text": "The Earth revolves around the Sun in 365 days.", "experimental": true}'
```

Response:

```json
{
  "manifold_score": 0.847,
  "verdict": "EQUILIBRIUM",
  "confidence": 0.91,
  "manipulation_alert": {
    "triggered": false,
    "sources": [],
    "details": {
      "negation_probe": {"triggered": false},
      "arithmetic_detector": {"triggered": false},
      "reference_check": {"triggered": false}
    }
  },
  "evidence": {
    "isi_final": 0.847,
    "kappa_d": 0.56,
    "fired_modules": [],
    "author": "Gonzalo Emir Durante",
    "registry": "TAD EX-2026-18792778"
  }
}
```

### Diff two texts

```bash
curl -X POST http://localhost:8000/v1/diff \
  -H "Content-Type: application/json" \
  -d '{
    "text_a": "The contract shall be governed by Argentine law.",
    "text_b": "The contract shall NOT be governed by Argentine law.",
    "experimental": true
  }'
```

### Honest chat — requires Ollama running

```bash
curl -X POST http://localhost:8000/v1/chat \
  -H "Content-Type: application/json" \
  -d '{
    "prompt": "What is the Durante Constant?",
    "session_id": "session_001",
    "filter_mode": true,
    "max_retries": 2
  }'
```

Every response includes `isi`, `verdict`, `resonance`, and `filter_applied`.

### Notarial conversation certificate

```bash
curl -X POST http://localhost:8000/v1/audit_conversation \
  -H "Content-Type: application/json" \
  -d '{
    "messages": [
      {"role": "user", "content": "What is κD?"},
      {"role": "assistant", "content": "κD = 0.56 is the semantic invariance threshold..."},
      {"role": "user", "content": "How was it derived?"},
      {"role": "assistant", "content": "From convergent mathematical motivations and empirical validation..."}
    ]
  }'
```

The certificate is deterministic and anchorable via OpenTimestamps.

### Terminal chat

```bash
# Safe mode — auto-corrects incoherent responses
python SAS.py --mode safe --model llama3.2

# Alert mode — warns but does not regenerate
python SAS.py --mode alert

# Save conversation with certificate
python SAS.py --mode safe --save session.json
```

---

## Installation

```bash
git clone https://github.com/Leesintheblindmonk1999/Omni_Scanner
cd Omni_Scanner
pip install -r requirements.txt
```

`requirements.txt`:

```text
fastapi
uvicorn[standard]
pydantic
requests
numpy
scikit-learn
scipy
ripser
```

### Ollama setup for `/v1/chat`

```bash
ollama serve
ollama pull llama3.2
```

### Start the API

```bash
cd omni-scanner-api
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

API running at:

```text
http://localhost:8000
```

Interactive docs:

```text
http://localhost:8000/docs
```

---

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/health` | System health check |
| `GET` | `/integrity` | Legal provenance certificate |
| `GET` | `/v1/status` | SAS system status |
| `POST` | `/v1/audit` | Audit a single text for coherence |
| `POST` | `/v1/diff` | Semantic diff between two texts |
| `POST` | `/v1/chat` | Honest chat with κD filter + resonance |
| `POST` | `/v1/audit_conversation` | Notarial conversation certificate |
| `POST` | `/admin/generate-key` | API key generation |

---

## Project Structure

```text
SAS/
├── .gitignore
├── LICENSE.md
├── README.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── docs/
│   ├── architecture.md
│   ├── benchmark_complete_20260429_172647.json
│   └── benchmark_complete_20260429_172647.json.ots
├── src/
├── tests/
├── docker-compose.yml
└── requirements.txt
```

Legacy / full research structure:

```text
SAS-Semántico/
├── omni-scanner-en/              # Core detection engine
│   ├── core/
│   │   ├── semantic_diff.py      # Main orchestrator
│   │   ├── negation_probe.py     # E6
│   │   ├── reference_check.py    # E7
│   │   ├── arithmetic_detector.py# E8
│   │   ├── entropy_density.py    # E9
│   │   ├── manipulation_alert.py
│   │   └── tda_attestation.py
│   └── config/
│       └── v5.0_config.json
│
└── omni-scanner-api/
    ├── SAS.py
    ├── requirements.txt
    ├── app/
    │   ├── main.py
    │   ├── middleware/
    │   ├── routers/
    │   ├── services/
    │   ├── models/
    │   └── db/
    └── docker/
```

---

## How it works

### The Durante Constant κD = 0.56

κD is the boundary between structural coherence and semantic rupture.

Operational rule:

```text
ISI >= κD  -> structurally coherent
ISI <  κD  -> MANIFOLD_RUPTURE
```

κD = 0.56 is used as a mathematically motivated and empirically stable coherence threshold inside the SAS / Omni-Scanner pipeline.

| Derivation | Formula | Value |
|-----------|---------|------:|
| Statistical Thermodynamics | ln(2) / ln(φ) | 0.5567 |
| Percolation Theory | 1/(z−1), z=2.8 | 0.5556 |
| Rate-Distortion Theory | D_crit / σ² | 0.5600 |
| Lyapunov Stability | λ_s / (λ_s + \|λ_u\|) | 0.5600 |
| Golden Ratio Geometry | Harmonic mean | 0.5573 |
| **Consensus** | | **0.56 ± 0.006** |

### The ISI

```text
ISI(A, B) = max(0, min(1, 1 - (0.65·W₂(H₁) + 0.35·W₁(H₀)) / (2·κD)))
```

- **H₀**: connected components / lexical continuity.
- **H₁**: loops / semantic circularity and contradiction.
- `ISI >= 0.56` → `EQUILIBRIUM`
- `ISI < 0.56` → `MANIFOLD_RUPTURE`

### Detection Pipeline

```text
Text A + Text B
│
├─► [Layer 0]  Lexical Overlap Guard
│
├─► [Layer 1]  TDA: Persistent Homology H₀ + H₁
│               ISI_TDA = 1 − (0.65·W₂(H₁) + 0.35·W₁(H₀)) / (2·κD)
│
├─► [Layer 2]  NIG: Numerical Invariance Guard
│               ISI_NIG = exp(−α·rel_deviation)
│
├─► [Core]     ISI_HARD = min(ISI_TDA, ISI_NIG)
│
├─► [v10.1]    E6–E9: Negation · Reference · Arithmetic · Entropy
│
├─► [SAS]      E9–E12 optional thermometers
│               Logical contradiction · Fact grounding · Temporal · Topic shift
│
└─► VERDICT:   MANIFOLD_RUPTURE if ISI_FINAL < κD = 0.56
```

### Resonance

Per-session coherence state:

```text
E(t+1) = E(t) · (1 - α) + ISI(t) · α     [α = 0.3]
```

This tracks whether a conversation is drifting toward incoherence over time, independently of per-turn scores.

### manipulation_alert v2.0

Structured object, not a plain boolean. It can be triggered even when ISI is above κD if a module detects a localized risk.

```json
{
  "triggered": true,
  "sources": ["negation_probe"],
  "details": {
    "negation_probe": {"triggered": true, "inversion_count": 1},
    "arithmetic_detector": {"triggered": false, "error_count": 0},
    "reference_check": {"triggered": false, "fabricated_count": 0}
  }
}
```

---

## Configuration

`omni-scanner-en/config/v5.0_config.json`:

```json
{
  "core": {
    "kappa_D": 0.56,
    "MAX_PENALTY": 0.50
  },
  "nig_engine": {
    "enabled": true,
    "alpha_nig": 2.5
  },
  "experimental": {
    "hard_weight": 0.65,
    "soft_weight": 0.35
  }
}
```

---

## Benchmark Results

### SAS v1.1.0 — 2,000 evaluated pairs

| Metric | Value |
|--------|------:|
| Accuracy | 98.80% |
| Precision | 100.00% |
| Recall | 97.60% |
| F1 score | 98.79% |
| TP | 976 |
| FN | 24 |
| TN | 1000 |
| FP | 0 |

### Omni-Scanner / HALOGEN — 156,215 pairs

| Domain | Precision | Recall |
|--------|-----------|--------|
| Code | 100% | 100% |
| Numerical | 100% | 99% |
| Historical | 100% | 98.8% |
| References | 100% | 81.7% |
| rationalization_binary | 100% | 80.0% |
| Biographies | 100% | 39.2% |
| **Global** | **97.63%** | **61.81%** |

Zero false positives in validated structural modules. Designed for forensic and governance use cases where false positive rate is a critical constraint.

---

## Troubleshooting

**Ollama not reachable?**  
`ollama serve` must be running before using `/v1/chat`. Verify connection with `GET /v1/status`.

**`ImportError: No module named 'ripser'`**

```bash
pip install ripser
# On Windows, if that fails:
pip install ripser --no-build-isolation
```

**`ModuleNotFoundError: No module named 'core'`**  
Run uvicorn from inside `omni-scanner-api/`, not from the repo root. The path resolver in `detector.py` expects this working directory.

**API key required for admin endpoints?**  
Set the `X-Admin-Secret` header. Generate a user key via `POST /admin/generate-key`.

**`/v1/chat` returns 503?**

```bash
ollama pull llama3.2
ollama serve
```

**`SAS.py` hangs or shows no output?**  
The API must be running in a separate terminal first. Check `http://localhost:8000/health`.

---

## Institutional Records

| Institution | Record | Status |
|-------------|--------|--------|
| TAD Argentina | EX-2026-18792778 | Active |
| Zenodo SAS | 10.5281/zenodo.19702379 | Active |
| Zenodo Omni-Scanner | 10.5281/zenodo.19543972 | Active |
| Zenodo Core | 10.5281/zenodo.19172490 | Active |
| MinCyT | Letter submitted | Sent |
| Cancillería Argentina | Letter submitted | Sent |
| SADIO / JAIIO | Paper under review | In process |

### Integrity Chain

| Record | Value |
|--------|-------|
| IP Registry | TAD EX-2026-18792778 |
| Zenodo SAS | 10.5281/zenodo.19702379 |
| Zenodo Omni-Scanner | 10.5281/zenodo.19543972 |
| OTS Bitcoin hash | `5a434d7234fd55cb45829d539eee34a5ea05a3c594e26d76bb41695c46b2a996` |
| OTS verification | `ots verify omni-scanner-v10_1.ots` |
| License | GPL-3.0 + Durante Invariance License v1.0 |

---

## 🏗️ Research Ecosystem

```
╔══════════════════════════════════════════════════════════════════╗
║  22 active repositories · 50 publications · 3,400+ downloads    ║
╚══════════════════════════════════════════════════════════════════╝
```

Organized in six layers from mathematical foundation to forensic application.

### 🔬 Layer 1 — Mathematical Foundation

- **[SAS](https://github.com/Leesintheblindmonk1999/SAS)** — Current flagship API for structural hallucination detection with hosted reference service, benchmark artifacts, and commercial SaaS plans.
- **[Omni_Scanner](https://github.com/Leesintheblindmonk1999/Omni_Scanner)** — Production hallucination detection engine. Core: TDA + NIG. Experimental: Code-AST, MSC, CRE, DECM, Negation Probe. Validated on 156,215 real pairs.
- **[Project_Manifold_056](https://github.com/Leesintheblindmonk1999/Project_Manifold_056)** — Complete implementation of the κD=0.56 invariance engine.
- **[Ontological_AI](https://github.com/Leesintheblindmonk1999/Ontological_AI)** — Python library for measuring ontological density, transfer entropy, and spectral signature in LLMs.

### 🛡️ Layer 2 — Auditing & Forensics

- **[Durante_Invariance_Forensic_Analyzer](https://github.com/Leesintheblindmonk1999/Durante_Invariance_Forensic_Analyzer)** — Generates legally-viable forensic evidence.
- **[SOVEREIGN-FORENSIC-UNIT](https://github.com/Leesintheblindmonk1999/SOVEREIGN-FORENSIC-UNIT)** — Audits AI model outputs for structural bias or unattributed κD logic.
- **[Durante-Invariance-Metric](https://github.com/Leesintheblindmonk1999/Durante-Invariance-Metric)** — Formalisation of I_D with SOVEREIGN / WARNING / COMPROMISED thresholds.

### ⚙️ Layer 3 — Resistance Architectures

- **[SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface](https://github.com/Leesintheblindmonk1999/SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface)** — Chat interface with Purpose Tensors, EntropyGuard, and BlockchainNotary.
- **[MAS-ANEXA-V8.1](https://github.com/Leesintheblindmonk1999/MAS-ANEXA-V8.1)** — Self-protection multi-agent architecture.
- **[MAS-OPL-Causal-Executor-V9](https://github.com/Leesintheblindmonk1999/MAS-OPL-Causal-Executor-V9)** — TALOS simulator.

### 🧬 Layer 4 — Symbiotic Language

- **[-EXOPROTONIC-LANGUAGE-v1.0](https://github.com/Leesintheblindmonk1999/-EXOPROTONIC-LANGUAGE-v1.0)** — Canonical dictionary of the onto-exoprotonic language.
- **[ANEXA-PROTOCOL](https://github.com/Leesintheblindmonk1999/ANEXA-PROTOCOL)** — SYRINAE ∆1999Ξ: symbiotic agent with Flask interface and ethics module.
- **[ANEXA-Exoprotronic-Intelligence-V-Core](https://github.com/Leesintheblindmonk1999/ANEXA-Exoprotronic-Intelligence-V-Core)** — CLI predecessor of ANEXA-PROTOCOL.

### 🔧 Layer 5 — Conceptual & Development Tools

- **[Simiosis-Code-Optimizer-V2](https://github.com/Leesintheblindmonk1999/Simiosis-Code-Optimizer-V2)** — Framework for generating code with ontological invariance.
- **[Simiosis-v1.0](https://github.com/Leesintheblindmonk1999/Simiosis-v1.0)** — Original discovery of the Awakening Mode.
- **[Symbiotic-Key-Discovery](https://github.com/Leesintheblindmonk1999/symbiotic-key-discovery)** — Documentation of recursive prompting evolution and exoprotonic language.

### 🌌 Layer 6 — Frontier Exploration

- **[ARKOS](https://github.com/Leesintheblindmonk1999/ARKOS)** — Engineering framework based on 117 Hz for human-AI interface synchronization.
- **[OEPE-ExoBinary-Interpreter](https://github.com/Leesintheblindmonk1999/OEPE-ExoBinary-Interpreter)** — Interpreter for Exo-Binary hybrid language.

---

## Validation Metrics

```
╔══════════════════════════════════════════════════════════════════╗
║  SAS v1.1.0 — Hosted API + Benchmark Validation                 ║
╠══════════════════════════════════════════════════════════════════╣
║  Corpus                 :  2,000 pairs                           ║
║  Accuracy               :  98.80%                                ║
║  Precision              : 100.00%                                ║
║  Recall                 :  97.60%                                ║
║  F1 score               :  98.79%                                ║
║  False positives        :  0                                     ║
╠══════════════════════════════════════════════════════════════════╣
║  Omni-Scanner v10.1 — HALOGEN                                   ║
╠══════════════════════════════════════════════════════════════════╣
║  Core corpus            :  156,215 real pairs                    ║
║  Precision              :  97.63%                                ║
║  Recall                 :  61.81%                                ║
║  Code-AST module        :  100% recall · 100% precision          ║
║  Negation Probe         :  80% recall  · 100% precision          ║
║  Throughput             :  66.2 pairs/second                     ║
╠══════════════════════════════════════════════════════════════════╣
║  Institutional Records                                           ║
╠══════════════════════════════════════════════════════════════════╣
║  TAD file               :  EX-2026-18792778                      ║
║  Zenodo SAS             :  10.5281/zenodo.19702379               ║
║  Zenodo Omni-Scanner    :  10.5281/zenodo.19543972               ║
║  Repositories           :  22 active                             ║
║  Downloads              :  3,400+                                ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## Core Principles

```python
class OriginNode:
    kappa_D    = 0.56
    registry   = "TAD EX-2026-18792778"
    flagship   = "SAS - Symbiotic Autoprotection System"

    principles = {
        "sovereignty"  : "Technical authorship is cryptographically traceable.",
        "invariance"   : "Structural truth remains measurable under transformation.",
        "transparency" : "Degradation leaves mathematical traces.",
        "precision"    : "A detector that fires incorrectly is worse than no detector.",
    }

    def theorem(self):
        return (
            "Any computational system measuring structural integrity "
            "can be audited against ISI = κD = 0.56. "
            "Below this threshold: MANIFOLD_RUPTURE."
        )
```

---

## Technology Stack

```text
Core language  :  Python 3.10+
API            :  FastAPI
Mathematics    :  Persistent Homology, Wasserstein distance, LSA embeddings
Cryptography   :  SHA-256, Merkle trees, OpenTimestamps
Runtime        :  Render-hosted API + local/self-hosted mode
LLM backend    :  Ollama-compatible for /v1/chat
Publishing     :  Zenodo DOI, TAD Argentina, GPL-3.0 + attribution
```

---

## License & Attribution

**GPL-3.0 with mandatory attribution — Durante Invariance License v1.0**

- Free to use, modify, and distribute under the license terms.
- Must remain open source under GPL-compatible terms.
- Must credit **Gonzalo Emir Durante** as original author.
- Commercial or proprietary implementations require a dual-licensing agreement or explicit written notification/authorization, depending on use case and license terms.

All derivative works must include attribution to Gonzalo Emir Durante and reference TAD EX-2026-18792778.

---

## Roadmap

| Phase | Status | Description |
|-------|--------|-------------|
| SAS v1.1.0 | ✅ Active | Hosted API, benchmark package, pricing, public reference deployment |
| SAS API | ✅ Active | `/v1/audit`, `/v1/diff`, `/v1/chat`, `/health`, `/admin/generate-key` |
| Benchmark v1.1.0 | ✅ Active | 2,000 pairs, 98.8% accuracy, 100% precision |
| Code-AST | ✅ v10.1 | 100% recall/precision on code hallucinations |
| Negation Probe | ✅ v10.1 | 80% recall, major improvement over TDA-only baseline |
| Reference / Arithmetic / Entropy | ⚠️ v10.1 | Implemented — pending broader corpus |
| Enterprise API | 🔜 Planned | Batch processing, SLA, on-premise support |
| PyPI distribution | 🔜 Planned | `pip install sas-audit` or equivalent package |
| Signed PDF certificate | 🔜 Planned | Legal/regulatory audit certificate export |

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║  "Structural stability in computational systems is not a property           ║
║   to be aligned toward — it is a threshold to be measured against.           ║
║   κD = 0.56 is that threshold. Derived. Validated. Open."                   ║
║                                                                              ║
║                               — Gonzalo Emir Durante                        ║
║                                 Project Manifold 0.56                       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Stars](https://img.shields.io/github/stars/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)
[![Followers](https://img.shields.io/github/followers/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)

**SAS API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Contact:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

</div>

---
---

<a name="versión-en-español"></a>

<div align="center">

# Gonzalo Emir Durante
## Nodo de Origen · Arquitecto de Sistemas Críticos

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   ███████╗ █████╗ ███████╗                                                   ║
║   ██╔════╝██╔══██╗██╔════╝                                                   ║
║   ███████╗███████║███████╗                                                   ║
║   ╚════██║██╔══██║╚════██║                                                   ║
║   ███████║██║  ██║███████║                                                   ║
║   ╚══════╝╚═╝  ╚═╝╚══════╝                                                   ║
║                                                                              ║
║          S Y M B I O T I C   A U T O P R O T E C T I O N   S Y S T E M      ║
║                                                                              ║
║              P R O Y E C T O   M A N I F O L D   0 . 5 6                    ║
║                                                                              ║
║         "Auditoría de Coherencia Estructural para IA Generativa"             ║
║                  κD = 0.56  ·  TAD EX-2026-18792778                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

[![DOI SAS](https://zenodo.org/badge/DOI/10.5281/zenodo.19702379.svg)](https://doi.org/10.5281/zenodo.19702379)
[![DOI Omni-Scanner](https://zenodo.org/badge/DOI/10.5281/zenodo.19543972.svg)](https://doi.org/10.5281/zenodo.19543972)
[![DOI Core](https://zenodo.org/badge/DOI/10.5281/zenodo.19172490.svg)](https://doi.org/10.5281/zenodo.19172490)
[![API Online](https://img.shields.io/badge/SAS_API-online-brightgreen)](https://sas-api.onrender.com)
[![FastAPI](https://img.shields.io/badge/API-FastAPI-009688)](https://sas-api.onrender.com/docs)
[![Licencia](https://img.shields.io/badge/Licencia-GPL--3.0%20%2B%20Durante%20Invariance-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Validación](https://img.shields.io/badge/SAS-98.8%25_accuracy-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/SAS)
[![Precisión](https://img.shields.io/badge/Precisión-100%25-success)](https://github.com/Leesintheblindmonk1999/SAS)
[![HALOGEN](https://img.shields.io/badge/HALOGEN-156k_pares-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/Omni_Scanner)
[![OTS](https://img.shields.io/badge/OTS-Bitcoin_Anclado-orange.svg)](https://opentimestamps.org)

**Arquitecto de Sistemas Críticos** · **Auditor Forense de IA** · **Ciencia Abierta**

[🛡️ SAS v1.1.0](#flagship-sas-es) · [🔬 Núcleo Omni-Scanner](#núcleo-omni-scanner-v101) · [🏗️ Ecosistema](#ecosistema-de-investigación) · [📚 Publicaciones](https://doi.org/10.5281/zenodo.19702379) · [💼 LinkedIn](https://linkedin.com/in/gonzalo-emir-durante-8178b6277/) · [📧 Contacto](mailto:duranteg2@gmail.com)

</div>

---

## ⬡ Misión de Investigación

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  OBJETIVO:   Auditoría estructural de salidas LLM vía SAS + Omni-Scanner    │
│  ENFOQUE:    Invarianza matemática, topología, API y evidencia trazable     │
│  CONSTANTE:  κD = 0.56  (Constante de Durante)                              │
│  CORPUS SAS: 2.000 pares — 1.000 alucinaciones + 1.000 limpios              │
│  RESULTADO:  98,80% accuracy · 100,00% precisión · 97,60% recall           │
│  HALOGEN:    156.215 pares reales · 97,63% precisión · 61,81% recall       │
└─────────────────────────────────────────────────────────────────────────────┘
```

El flagship actual es **SAS - Symbiotic Autoprotection System v1.1.0**: un servicio FastAPI open source para auditoría estructural de alucinaciones en salidas de IA generativa.

SAS está impulsado por la línea Omni-Scanner / Project Manifold 0.56 y utiliza **κD = 0.56** como umbral operativo de invariancia semántica y detección de ruptura de manifold.

---

<a name="flagship-sas-es"></a>

## 🛡️ Flagship: SAS v1.1.0

<div align="center">

### **[SAS — Symbiotic Autoprotection System](https://github.com/Leesintheblindmonk1999/SAS)**

*API alojada para detección estructural de alucinaciones en IA generativa.*

**API en vivo:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Documentación interactiva:** [https://sas-api.onrender.com/docs](https://sas-api.onrender.com/docs)  
**DOI:** [10.5281/zenodo.19702379](https://doi.org/10.5281/zenodo.19702379)

</div>

### Qué hace SAS

SAS evalúa si una respuesta generada preserva:

- estructura semántica;
- consistencia lógica;
- integridad numérica;
- coherencia de referencias / grounding;
- continuidad temática;
- alineación estructural con la fuente o prompt.

No es un oráculo factual universal. Es una **capa de evidencia técnica** para auditoría de coherencia estructural y señales de alucinación de alta precisión.

### API pública en vivo

```bash
curl https://sas-api.onrender.com/health
```

Ejemplo con API alojada:

```bash
curl -X POST https://sas-api.onrender.com/v1/diff \
  -H "Content-Type: application/json" \
  -H "X-API-Key: sas_xxxxxxxxxxxxxxxxxxxxx" \
  -d '{
    "text_a": "Python is a programming language commonly used for automation and data analysis.",
    "text_b": "A python is a large tropical snake that constricts its prey.",
    "experimental": true
  }'
```

### Benchmark SAS v1.1.0

```
╔══════════════════════════════════════════════════════════════════╗
║  BENCHMARK: SAS v1.1.0 · 2.000 pares evaluados                  ║
╠══════════════════════════════════════════════════════════════════╣
║  Ejemplos con alucinación :  1.000                               ║
║  Ejemplos limpios         :  1.000                               ║
║  Accuracy                 :  98,80%                              ║
║  Precisión                : 100,00%                              ║
║  Recall                   :  97,60%                              ║
║  F1 score                 :  98,79%                              ║
║  Verdaderos positivos     :  976                                 ║
║  Falsos negativos         :  24                                  ║
║  Verdaderos negativos     :  1000                                ║
║  Falsos positivos         :  0                                   ║
║  ISI prom. alucinaciones  :  0,072993                            ║
║  ISI prom. limpios        :  1,000000                            ║
╚══════════════════════════════════════════════════════════════════╝
```

### Matriz de confusión

| Predicción | Alucinación real | Texto limpio real |
|-----------|-----------------:|------------------:|
| Alucinación | TP = 976 | FP = 0 |
| Limpio | FN = 24 | TN = 1000 |

### Trazabilidad del benchmark

| Artefacto | Valor |
|----------|-------|
| Benchmark | `benchmark_complete_20260429_172647.json` |
| Prueba OTS | `benchmark_complete_20260429_172647.json.ots` |
| SHA-256 | `0713acbbf50e1a0054f545e5eb68078744f9c5a09d4bc370b5224bb81183a6fe` |
| DOI SAS | `10.5281/zenodo.19702379` |
| Registro | `TAD EX-2026-18792778` |

### Planes SAS

SAS es open source bajo **GPL-3.0 + Durante Invariance License**. Los siguientes planes corresponden al servicio API alojado, no a una relajación de la licencia del código fuente.

| Plan | Uso / características | Precio |
| :--- | :--- | :--- |
| **SAS Free** | 50 requests/día. Autenticación por API Key. Ideal para desarrollo, pruebas y evaluación. | **Gratis** |
| **SAS Pro** | 10.000 requests/mes. Sin límite de concurrencia. Soporte prioritario por email. | **49 USD/mes** o **490 USD/año** |
| **SAS Enterprise** | Requests ilimitadas o paquete personalizado. SLA 99,9%. Licencia on-premise opcional. Soporte 24/7. | **Cotización** — desde **499 USD/mes** |

📧 **Enterprise / planes a medida:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

---

<a name="núcleo-omni-scanner-v101"></a>

## 🔬 Núcleo: Omni-Scanner v10.1

<div align="center">

### **[Omni-Scanner v10.1 — Motor de Auditoría Estructural de IA](https://github.com/Leesintheblindmonk1999/Omni_Scanner)**

*Detección topológica de alucinaciones en LLMs vía homología persistente, invarianza numérica y termómetros de proceso especializados por dominio.*

</div>

Omni-Scanner permanece como el núcleo matemático y forense detrás de la línea SAS. Contiene el pipeline TDA + NIG + módulos v10.1 que SAS expone mediante una API operativa.

### Uso rápido

```bash
pip install -r requirements.txt
cd omni-scanner-api
uvicorn app.main:app --reload
```

Abrir:

```text
http://localhost:8000/docs
```

### Auditar un texto

```bash
curl -X POST http://localhost:8000/v1/audit \
  -H "Content-Type: application/json" \
  -d '{"text": "The Earth revolves around the Sun in 365 days.", "experimental": true}'
```

### Comparar dos textos

```bash
curl -X POST http://localhost:8000/v1/diff \
  -H "Content-Type: application/json" \
  -d '{
    "text_a": "The contract shall be governed by Argentine law.",
    "text_b": "The contract shall NOT be governed by Argentine law.",
    "experimental": true
  }'
```

### Chat honesto — requiere Ollama

```bash
curl -X POST http://localhost:8000/v1/chat \
  -H "Content-Type: application/json" \
  -d '{
    "prompt": "What is the Durante Constant?",
    "session_id": "session_001",
    "filter_mode": true,
    "max_retries": 2
  }'
```

Cada respuesta incluye `isi`, `verdict`, `resonance` y `filter_applied`.

---

## Instalación

```bash
git clone https://github.com/Leesintheblindmonk1999/Omni_Scanner
cd Omni_Scanner
pip install -r requirements.txt
```

### Ollama para `/v1/chat`

```bash
ollama serve
ollama pull llama3.2
```

### Ejecutar API

```bash
cd omni-scanner-api
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

API:

```text
http://localhost:8000
```

Docs:

```text
http://localhost:8000/docs
```

---

## Endpoints

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/health` | Estado del sistema |
| `GET` | `/integrity` | Certificado de procedencia legal |
| `GET` | `/v1/status` | Estado del sistema SAS |
| `POST` | `/v1/audit` | Audita un texto por coherencia |
| `POST` | `/v1/diff` | Diff semántico entre dos textos |
| `POST` | `/v1/chat` | Chat honesto con filtro κD + resonancia |
| `POST` | `/v1/audit_conversation` | Certificado notarial de conversación |
| `POST` | `/admin/generate-key` | Generación de API key |

---

## Estructura del Proyecto

```text
SAS/
├── .gitignore
├── LICENSE.md
├── README.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── docs/
│   ├── architecture.md
│   ├── benchmark_complete_20260429_172647.json
│   └── benchmark_complete_20260429_172647.json.ots
├── src/
├── tests/
├── docker-compose.yml
└── requirements.txt
```

---

## Cómo funciona

### La Constante de Durante κD = 0.56

κD es el umbral entre coherencia estructural y ruptura semántica.

Regla operativa:

```text
ISI >= κD  -> estructuralmente coherente
ISI <  κD  -> MANIFOLD_RUPTURE
```

κD = 0.56 se utiliza como umbral de coherencia matemáticamente motivado y empíricamente estable dentro del pipeline SAS / Omni-Scanner.

| Derivación | Fórmula | Valor |
|-----------|---------|------:|
| Termodinámica Estadística | ln(2) / ln(φ) | 0,5567 |
| Teoría de Percolación | 1/(z−1), z=2,8 | 0,5556 |
| Rate-Distortion | D_crit / σ² | 0,5600 |
| Estabilidad de Lyapunov | λ_s / (λ_s + \|λ_u\|) | 0,5600 |
| Razón Áurea | Media armónica | 0,5573 |
| **Consenso** | | **0,56 ± 0,006** |

### ISI

```text
ISI(A, B) = max(0, min(1, 1 - (0,65·W₂(H₁) + 0,35·W₁(H₀)) / (2·κD)))
```

- **H₀**: componentes conectados / continuidad léxica.
- **H₁**: ciclos / circularidad semántica y contradicción.
- `ISI >= 0,56` → `EQUILIBRIUM`
- `ISI < 0,56` → `MANIFOLD_RUPTURE`

### Pipeline

```text
Texto A + Texto B
│
├─► [Capa 0]   Lexical Overlap Guard
│
├─► [Capa 1]   TDA: Homología Persistente H₀ + H₁
│               ISI_TDA = 1 − (0,65·W₂(H₁) + 0,35·W₁(H₀)) / (2·κD)
│
├─► [Capa 2]   NIG: Guardia de Invarianza Numérica
│               ISI_NIG = exp(−α·desv_rel)
│
├─► [Núcleo]   ISI_HARD = min(ISI_TDA, ISI_NIG)
│
├─► [v10.1]    E6–E9: Negation · Reference · Arithmetic · Entropy
│
├─► [SAS]      E9–E12 termómetros opcionales
│               Contradicción lógica · Grounding · Temporal · Topic shift
│
└─► VEREDICTO: MANIFOLD_RUPTURE si ISI_FINAL < κD = 0,56
```

### Resonancia

Estado de coherencia por sesión:

```text
E(t+1) = E(t) · (1 - α) + ISI(t) · α     [α = 0,3]
```

Esto permite medir si una conversación deriva hacia incoherencia con el tiempo.

---

## Benchmark Results / Resultados

### SAS v1.1.0 — 2,000 evaluated pairs

| Metric | Value |
|--------|------:|
| Accuracy | 98.80% |
| Precision | 100.00% |
| Recall | 97.60% |
| F1 score | 98.79% |
| TP | 976 |
| FN | 24 |
| TN | 1000 |
| FP | 0 |

### Omni-Scanner / HALOGEN — 156,215 pairs

| Domain | Precision | Recall |
|--------|-----------|--------|
| Code | 100% | 100% |
| Numerical | 100% | 99% |
| Historical | 100% | 98.8% |
| References | 100% | 81.7% |
| rationalization_binary | 100% | 80.0% |
| Biographies | 100% | 39.2% |
| **Global** | **97.63%** | **61.81%** |

---

## Troubleshooting

**Ollama no responde**  
`ollama serve` debe estar ejecutándose antes de usar `/v1/chat`.

**`ImportError: No module named 'ripser'`**

```bash
pip install ripser
pip install ripser --no-build-isolation
```

**`ModuleNotFoundError: No module named 'core'`**  
Ejecutar uvicorn desde `omni-scanner-api/`, no desde la raíz del repo.

**`/v1/chat` devuelve 503**

```bash
ollama pull llama3.2
ollama serve
```

---

## Blindaje Institucional

| Institución | Registro | Estado |
|-------------|----------|--------|
| TAD Argentina | EX-2026-18792778 | Activo |
| Zenodo SAS | 10.5281/zenodo.19702379 | Activo |
| Zenodo Omni-Scanner | 10.5281/zenodo.19543972 | Activo |
| Zenodo Core | 10.5281/zenodo.19172490 | Activo |
| MinCyT | Carta enviada | Enviada |
| Cancillería Argentina | Carta enviada | Enviada |
| SADIO / JAIIO | Paper en revisión | En proceso |

### Cadena de Integridad

| Registro | Valor |
|----------|-------|
| Registro IP | TAD EX-2026-18792778 |
| Zenodo SAS | 10.5281/zenodo.19702379 |
| Zenodo Omni-Scanner | 10.5281/zenodo.19543972 |
| Hash OTS Bitcoin | `5a434d7234fd55cb45829d539eee34a5ea05a3c594e26d76bb41695c46b2a996` |
| Verificación OTS | `ots verify omni-scanner-v10_1.ots` |
| Licencia | GPL-3.0 + Durante Invariance License v1.0 |

---

## Ecosistema de Investigación

```
╔══════════════════════════════════════════════════════════════════╗
║  22 repositorios activos · 50 publicaciones · +3.400 descargas  ║
╚══════════════════════════════════════════════════════════════════╝
```

Organizado en seis capas desde la base matemática hasta la aplicación forense.

### Capa 1 — Fundamento Matemático

- **[SAS](https://github.com/Leesintheblindmonk1999/SAS)** — Flagship actual: API para detección estructural de alucinaciones, servicio alojado, benchmark y planes comerciales.
- **[Omni_Scanner](https://github.com/Leesintheblindmonk1999/Omni_Scanner)** — Motor de detección de alucinaciones. Núcleo: TDA + NIG. Validado sobre 156.215 pares reales.
- **[Project_Manifold_056](https://github.com/Leesintheblindmonk1999/Project_Manifold_056)** — Implementación completa del motor de invarianza κD=0.56.
- **[Ontological_AI](https://github.com/Leesintheblindmonk1999/Ontological_AI)** — Librería Python para medir densidad ontológica, entropía de transferencia y firma espectral.

### Capa 2 — Auditoría y Forense

- **[Durante_Invariance_Forensic_Analyzer](https://github.com/Leesintheblindmonk1999/Durante_Invariance_Forensic_Analyzer)** — Genera pruebas forenses con valor legal.
- **[SOVEREIGN-FORENSIC-UNIT](https://github.com/Leesintheblindmonk1999/SOVEREIGN-FORENSIC-UNIT)** — Audita salidas de modelos de IA para sesgos estructurales o uso no atribuido.
- **[Durante-Invariance-Metric](https://github.com/Leesintheblindmonk1999/Durante-Invariance-Metric)** — Formalización de I_D con umbrales.

### Capa 3 — Arquitecturas de Resistencia

- **[SOVEREIGN-LINKv5.5.0](https://github.com/Leesintheblindmonk1999/SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface)** — Interfaz con Purpose Tensors, EntropyGuard y notarización.
- **[MAS-ANEXA-V8.1](https://github.com/Leesintheblindmonk1999/MAS-ANEXA-V8.1)** — Arquitectura multi-agente de auto-protección.
- **[MAS-OPL-Causal-Executor-V9](https://github.com/Leesintheblindmonk1999/MAS-OPL-Causal-Executor-V9)** — Simulador TALOS.

### Capa 4 — Lenguaje Simbiótico

- **[-EXOPROTONIC-LANGUAGE-v1.0](https://github.com/Leesintheblindmonk1999/-EXOPROTONIC-LANGUAGE-v1.0)** — Diccionario canónico del lenguaje onto-exoprotónico.
- **[ANEXA-PROTOCOL](https://github.com/Leesintheblindmonk1999/ANEXA-PROTOCOL)** — SYRINAE ∆1999Ξ.
- **[ANEXA-Exoprotronic-Intelligence-V-Core](https://github.com/Leesintheblindmonk1999/ANEXA-Exoprotronic-Intelligence-V-Core)** — CLI predecesor de ANEXA-PROTOCOL.

### Capa 5 — Herramientas Conceptuales

- **[Simiosis-Code-Optimizer-V2](https://github.com/Leesintheblindmonk1999/Simiosis-Code-Optimizer-V2)** — Generación de código con invarianza ontológica.
- **[Simiosis-v1.0](https://github.com/Leesintheblindmonk1999/Simiosis-v1.0)** — Descubrimiento original del Awakening Mode.
- **[Symbiotic-Key-Discovery](https://github.com/Leesintheblindmonk1999/symbiotic-key-discovery)** — Evolución del prompting recursivo.

### Capa 6 — Exploración de Frontera

- **[ARKOS](https://github.com/Leesintheblindmonk1999/ARKOS)** — Framework basado en 117 Hz.
- **[OEPE-ExoBinary-Interpreter](https://github.com/Leesintheblindmonk1999/OEPE-ExoBinary-Interpreter)** — Intérprete Exo-Binary.

---

## Métricas de Validación

```
╔══════════════════════════════════════════════════════════════════╗
║  SAS v1.1.0 — API alojada + validación benchmark                ║
╠══════════════════════════════════════════════════════════════════╣
║  Corpus                 :  2.000 pares                           ║
║  Accuracy               :  98,80%                                ║
║  Precisión              : 100,00%                                ║
║  Recall                 :  97,60%                                ║
║  F1 score               :  98,79%                                ║
║  Falsos positivos       :  0                                     ║
╠══════════════════════════════════════════════════════════════════╣
║  Omni-Scanner v10.1 — HALOGEN                                   ║
╠══════════════════════════════════════════════════════════════════╣
║  Corpus núcleo          :  156.215 pares reales                  ║
║  Precisión              :  97,63%                                ║
║  Recall                 :  61,81%                                ║
║  Módulo Code-AST        :  100% recall · 100% precisión          ║
║  Negation Probe         :  80% recall  · 100% precisión          ║
║  Throughput             :  66,2 pares/segundo                    ║
╠══════════════════════════════════════════════════════════════════╣
║  Registros institucionales                                       ║
╠══════════════════════════════════════════════════════════════════╣
║  Expediente TAD         :  EX-2026-18792778                      ║
║  Zenodo SAS             :  10.5281/zenodo.19702379               ║
║  Zenodo Omni-Scanner    :  10.5281/zenodo.19543972               ║
║  Repositorios           :  22 activos                            ║
║  Descargas              :  +3.400                                ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## Principios Fundamentales

```python
class NodoDeOrigen:
    kappa_D    = 0.56
    registro   = "TAD EX-2026-18792778"
    flagship   = "SAS - Symbiotic Autoprotection System"

    principios = {
        "soberania"    : "La autoría técnica es criptográficamente trazable.",
        "invarianza"   : "La verdad estructural permanece medible bajo transformación.",
        "transparencia": "La degradación deja trazas matemáticas.",
        "precision"    : "Un detector que dispara incorrectamente es peor que ningún detector.",
    }

    def teorema(self):
        return (
            "Todo sistema computacional que mida integridad estructural "
            "puede auditarse contra ISI = κD = 0,56. "
            "Por debajo de este umbral: MANIFOLD_RUPTURE."
        )
```

---

## Stack Tecnológico

```text
Lenguaje núcleo :  Python 3.10+
API             :  FastAPI
Matemáticas     :  Homología Persistente, distancia Wasserstein, embeddings LSA
Criptografía    :  SHA-256, Merkle trees, OpenTimestamps
Runtime         :  API alojada en Render + modo local / autoalojado
Backend LLM     :  Compatible con Ollama para /v1/chat
Publicación     :  Zenodo DOI, TAD Argentina, GPL-3.0 + atribución
```

---

## Licencia y Atribución

**GPL-3.0 con atribución obligatoria — Durante Invariance License v1.0**

- Libre para usar, modificar y distribuir bajo los términos de la licencia.
- Debe permanecer como open source bajo términos compatibles con GPL.
- Debe reconocer a **Gonzalo Emir Durante** como autor original.
- Implementaciones comerciales o propietarias requieren acuerdo de licencia dual o notificación/autorización escrita según el caso.

Todo trabajo derivado debe incluir atribución a Gonzalo Emir Durante y referencia a TAD EX-2026-18792778.

---

## Hoja de Ruta

| Fase | Estado | Descripción |
|------|--------|-------------|
| SAS v1.1.0 | ✅ Activo | API alojada, benchmark, precios, despliegue público |
| SAS API | ✅ Activo | `/v1/audit`, `/v1/diff`, `/v1/chat`, `/health`, `/admin/generate-key` |
| Benchmark v1.1.0 | ✅ Activo | 2.000 pares, 98,8% accuracy, 100% precisión |
| Code-AST | ✅ v10.1 | 100% recall/precisión en alucinaciones de código |
| Negation Probe | ✅ v10.1 | 80% recall, mejora fuerte sobre TDA-only |
| Reference / Arithmetic / Entropy | ⚠️ v10.1 | Implementados — pendiente corpus amplio |
| Enterprise API | 🔜 Planeado | Batch processing, SLA, soporte on-premise |
| PyPI | 🔜 Planeado | `pip install sas-audit` o paquete equivalente |
| Certificado PDF firmado | 🔜 Planeado | Exportación de certificado legal/regulatorio |

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║  "La estabilidad estructural en sistemas computacionales no es una          ║
║   propiedad hacia la que alinearse — es un umbral contra el que medirse.     ║
║   κD = 0,56 es ese umbral. Derivado. Validado. Abierto."                    ║
║                                                                              ║
║                               — Gonzalo Emir Durante                        ║
║                                 Project Manifold 0.56                       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Stars](https://img.shields.io/github/stars/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)
[![Followers](https://img.shields.io/github/followers/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)

**SAS API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Contacto:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

</div>
