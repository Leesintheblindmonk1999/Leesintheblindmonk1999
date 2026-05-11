<div align="center">

### 🌐 Language / Idioma

[🇺🇸 English](#english-version) &nbsp;&nbsp;|&nbsp;&nbsp; [🇦🇷 Español](#versión-en-español)

</div>

---

<a name="english-version"></a>

<div align="center">

# Gonzalo Emir Durante
## Origin Node · Critical Systems Architect · AI Forensic Auditor

```text
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
[![SAS API](https://img.shields.io/badge/SAS_API-online-brightgreen)](https://sas-api.onrender.com)
[![FastAPI](https://img.shields.io/badge/API-FastAPI-009688)](https://sas-api.onrender.com/docs)
[![PyPI](https://img.shields.io/pypi/v/sas-client?label=sas-client&color=blue)](https://pypi.org/project/sas-client/)
[![License](https://img.shields.io/badge/License-GPL--3.0%20%2B%20Durante%20Invariance-blue.svg)](https://github.com/Leesintheblindmonk1999/SAS/blob/main/LICENSE.md)
[![SAS Benchmark](https://img.shields.io/badge/SAS-98.80%25_accuracy-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/SAS)
[![Precision](https://img.shields.io/badge/Precision-100%25-success)](https://github.com/Leesintheblindmonk1999/SAS)
[![OTS](https://img.shields.io/badge/OpenTimestamps-Bitcoin_Anchored-orange.svg)](https://opentimestamps.org)

**AI structural coherence auditing · κD = 0.56 · Open science · Public API · PyPI client**

[🛡️ SAS](#-flagship-sas) · [⚡ Live Demo](#try-it-now--no-api-key-required) · [🐍 Python Client](#python-client) · [💼 Plans](#sas-hosted-api-plans) · [🏗️ Ecosystem](#-research--engineering-ecosystem) · [📧 Contact](mailto:duranteg2@gmail.com)

</div>

---

## ⬡ Current Mission

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│  OBJECTIVE:  Structural auditing of generative AI outputs                    │
│  METHOD:     κD = 0.56 + ISI + TDA + NIG + specialized detection modules     │
│  OUTPUT:     auditable evidence: ISI, verdict, triggered modules, latency    │
│  ACCESS:     public demo, hosted API, Python SDK, CLI, self-hosted option    │
│  STATUS:     public infrastructure online and under active development       │
└─────────────────────────────────────────────────────────────────────────────┘
```

I build technical systems for detecting structural instability, semantic rupture, and selected hallucination patterns in generative AI outputs.

The current flagship is **SAS — Symbiotic Autoprotection System**: a FastAPI-based structural coherence audit layer using **κD = 0.56** as its operational threshold.

SAS is not presented as a universal factual oracle. It is a technical evidence layer for structural coherence auditing.

---

## 🛡️ Flagship: SAS

<div align="center">

### **[SAS — Symbiotic Autoprotection System](https://github.com/Leesintheblindmonk1999/SAS)**

**Hosted API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Interactive API Docs:** [https://sas-api.onrender.com/docs](https://sas-api.onrender.com/docs)  
**Landing + Live Demo:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**PyPI Client:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**DOI:** [10.5281/zenodo.19702379](https://doi.org/10.5281/zenodo.19702379)

</div>

### What SAS measures

SAS evaluates whether a generated response preserves:

- semantic structure;
- logical consistency;
- numerical integrity;
- reference / grounding coherence;
- topic continuity;
- structural alignment with the source or prompt.

Operational interpretation:

```text
ISI >= κD  -> structural coherence preserved
ISI <  κD  -> possible manifold rupture / hallucination signal
```

Core threshold:

```text
κD = 0.56
```

---

## Try it now — no API key required

**Interactive demo:**  
[https://leesintheblindmonk1999.github.io/sas-landing/#demo](https://leesintheblindmonk1999.github.io/sas-landing/#demo)

The public demo uses the same source-vs-response forensic comparison logic as `/v1/diff`.

```bash
curl -X POST https://sas-api.onrender.com/public/demo/audit \
  -H "Content-Type: application/json" \
  -d '{
    "source": "The Eiffel Tower is located in Paris, France, and was built in 1889.",
    "response": "The Eiffel Tower is located in Berlin, Germany, and was built in 1950."
  }'
```

Public demo constraints:

- no API key required;
- max 2,000 characters per field;
- simple rate limit per anonymized IP hash;
- full input text is not stored;
- response includes ISI, κD, verdict, triggered modules, and latency.

---

## Python Client

Install:

```bash
pip install sas-client
```

Use from Python:

```python
from sas_client import SASClient

client = SASClient(api_key="YOUR_API_KEY")

result = client.diff(
    text_a="Python is a programming language used for data analysis.",
    text_b="A python is a large tropical snake."
)

print(result["isi"])
print(result["verdict"])
print(result.get("evidence", {}).get("fired_modules"))
```

Use from CLI:

```bash
sas health
sas public-stats
sas public-activity --limit 10
sas --api-key YOUR_API_KEY diff "source text" "response to audit"
```

Links:

- **PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)
- **Client repository:** [https://github.com/Leesintheblindmonk1999/sas-client](https://github.com/Leesintheblindmonk1999/sas-client)

---

## SAS Benchmark

```text
╔══════════════════════════════════════════════════════════════════╗
║  BENCHMARK: SAS · 2,000 evaluated text pairs                    ║
╠══════════════════════════════════════════════════════════════════╣
║  Hallucination examples :  1,000                                ║
║  Clean examples         :  1,000                                ║
║  Accuracy               :  98.80%                               ║
║  Precision              : 100.00%                               ║
║  Recall                 :  97.60%                               ║
║  F1 score               :  98.79%                               ║
║  True Positives         :  976                                  ║
║  False Negatives        :  24                                   ║
║  True Negatives         :  1000                                 ║
║  False Positives        :  0                                    ║
║  Avg ISI hallucination  :  0.072993                             ║
║  Avg ISI clean          :  1.000000                             ║
╚══════════════════════════════════════════════════════════════════╝
```

### Confusion Matrix

| Prediction | Actual hallucination | Actual clean |
|---|---:|---:|
| Hallucination | TP = 976 | FP = 0 |
| Clean | FN = 24 | TN = 1000 |

### Traceability

| Artifact | Value |
|---|---|
| Benchmark file | `benchmark_complete_20260429_172647.json` |
| OTS proof | `benchmark_complete_20260429_172647.json.ots` |
| SHA-256 | `0713acbbf50e1a0054f545e5eb68078744f9c5a09d4bc370b5224bb81183a6fe` |
| DOI SAS | `10.5281/zenodo.19702379` |
| Registry | `TAD EX-2026-18792778` |

---

## Public API Endpoints

| Method | Endpoint | Auth | Description |
|---|---|---|---|
| `GET` | `/health` | None | Health check |
| `GET` | `/readyz` | None | Readiness |
| `GET` | `/integrity` | None | Technical and legal provenance certificate |
| `POST` | `/public/demo/audit` | None | Public source-vs-response demo |
| `GET` | `/public/stats` | None | Anonymized usage stats |
| `GET` | `/public/activity` | None | Anonymized activity feed |
| `POST` | `/v1/audit` | API Key | Structural audit |
| `POST` | `/v1/diff` | API Key | Forensic diff between two texts |
| `POST` | `/v1/chat` | API Key | Chat endpoint with SAS filtering |
| `GET` | `/v1/metrics` | Admin | Admin usage metrics |
| `POST` | `/admin/generate-key` | Admin | Admin API key generation |

---

## SAS Hosted API Plans

SAS is open source under **GPL-3.0 + Durante Invariance License**.  
The following plans refer to the hosted SAS API service, support, commercial integration, or enterprise licensing.

| Plan | Usage / Features | Price |
| :--- | :--- | :--- |
| **SAS Free** | 50 requests/day. API key authentication. Individual testing, evaluation, and development. | **Free** |
| **SAS Developer / Pro** | 10,000 requests/month. Hosted API access, API key, basic email support. | **USD 99/month** |
| **SAS Team** | 50,000 requests/month. Team usage, priority support, internal validation workflows. | **USD 299/month** |
| **SAS Enterprise Cloud** | High-volume usage or custom request package. Direct support, private integration, SLA by agreement. | **From USD 1,500/month** |
| **SAS On-Premise License** | Private deployment in customer infrastructure. Commercial license, implementation support, internal integration. | **From USD 15,000/year** |
| **Technical Pilot** | Initial audit, guided integration, technical report, and validation on customer-specific cases. | **USD 1,500–3,000 one-time payment** |

📧 **Commercial inquiries, Enterprise, On-Premise, or technical pilot:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

---

## 🔬 Core Engine: Omni-Scanner

<div align="center">

### **[Omni-Scanner — Structural Hallucination Auditing Engine](https://github.com/Leesintheblindmonk1999/Omni_Scanner)**

</div>

Omni-Scanner is the mathematical and forensic research line behind SAS. It contains the TDA + NIG + process-thermometer pipeline that SAS exposes operationally through a hosted API.

### HALOGEN corpus summary

| Domain | Precision | Recall |
|---|---:|---:|
| Code | 100% | 100% |
| Numerical | 100% | 99% |
| Historical | 100% | 98.8% |
| References | 100% | 81.7% |
| rationalization_binary | 100% | 80.0% |
| Biographies | 100% | 39.2% |
| **Global** | **97.63%** | **61.81%** |

---

## 🌐 Distribution Ecosystem

### sas-client — Official Python SDK / CLI

```bash
pip install sas-client
```

| Interface | Example |
|---|---|
| Python | `client.diff(text_a="source", text_b="response")` |
| CLI | `sas --api-key YOUR_API_KEY diff "source" "response"` |
| Public endpoints | `sas health`, `sas public-stats`, `sas public-activity --limit 10` |

**PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**Repo:** [https://github.com/Leesintheblindmonk1999/sas-client](https://github.com/Leesintheblindmonk1999/sas-client)

### sas-landing — Live public landing

Interactive landing page with:

- ES / EN language toggle;
- LIGHT / DARK / TECH themes;
- live API health;
- public demo with no API key;
- public stats and anonymized activity;
- benchmark summary;
- pricing and commercial contact.

**Live:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**Repo:** [https://github.com/Leesintheblindmonk1999/sas-landing](https://github.com/Leesintheblindmonk1999/sas-landing)

---

## 🏗️ Research & Engineering Ecosystem

### Layer 1 — Mathematical Foundation

- **[SAS](https://github.com/Leesintheblindmonk1999/SAS)** — Flagship API for structural hallucination detection, hosted reference service, benchmark artifacts, Python client, public demo, and commercial plans.
- **[Omni_Scanner](https://github.com/Leesintheblindmonk1999/Omni_Scanner)** — Hallucination detection engine. Core: TDA + NIG. Validated on 156,215 real pairs.
- **[Project_Manifold_056](https://github.com/Leesintheblindmonk1999/Project_Manifold_056)** — Implementation of the κD=0.56 invariance engine.
- **[Ontological_AI](https://github.com/Leesintheblindmonk1999/Ontological_AI)** — Library for ontological density, transfer entropy, and spectral signature research.

### Layer 2 — Auditing & Forensics

- **[Durante_Invariance_Forensic_Analyzer](https://github.com/Leesintheblindmonk1999/Durante_Invariance_Forensic_Analyzer)** — Forensic evidence generation.
- **[SOVEREIGN-FORENSIC-UNIT](https://github.com/Leesintheblindmonk1999/SOVEREIGN-FORENSIC-UNIT)** — Structural analysis of AI outputs.
- **[Durante-Invariance-Metric](https://github.com/Leesintheblindmonk1999/Durante-Invariance-Metric)** — Formalization of invariance metrics.

### Layer 3 — Resistance Architectures

- **[SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface](https://github.com/Leesintheblindmonk1999/SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface)** — Chat interface with purpose tensors, EntropyGuard, and notarization.
- **[MAS-ANEXA-V8.1](https://github.com/Leesintheblindmonk1999/MAS-ANEXA-V8.1)** — Multi-agent self-protection architecture.
- **[MAS-OPL-Causal-Executor-V9](https://github.com/Leesintheblindmonk1999/MAS-OPL-Causal-Executor-V9)** — TALOS simulator.

### Layer 4 — Symbiotic Language

- **[-EXOPROTONIC-LANGUAGE-v1.0](https://github.com/Leesintheblindmonk1999/-EXOPROTONIC-LANGUAGE-v1.0)** — Onto-exoprotonic language dictionary.
- **[ANEXA-PROTOCOL](https://github.com/Leesintheblindmonk1999/ANEXA-PROTOCOL)** — SYRINAE ∆1999Ξ symbolic-ethical protocol.
- **[ANEXA-Exoprotronic-Intelligence-V-Core](https://github.com/Leesintheblindmonk1999/ANEXA-Exoprotronic-Intelligence-V-Core)** — CLI predecessor of ANEXA-PROTOCOL.

### Layer 5 — Conceptual & Development Tools

- **[Simiosis-Code-Optimizer-V2](https://github.com/Leesintheblindmonk1999/Simiosis-Code-Optimizer-V2)** — Code generation with ontological invariance.
- **[Simiosis-v1.0](https://github.com/Leesintheblindmonk1999/Simiosis-v1.0)** — Original Awakening Mode documentation.
- **[Symbiotic-Key-Discovery](https://github.com/Leesintheblindmonk1999/symbiotic-key-discovery)** — Recursive prompting and symbolic evolution record.

### Layer 6 — Frontier Exploration

- **[ARKOS](https://github.com/Leesintheblindmonk1999/ARKOS)** — Human-AI interface synchronization research based on 117 Hz.
- **[OEPE-ExoBinary-Interpreter](https://github.com/Leesintheblindmonk1999/OEPE-ExoBinary-Interpreter)** — Exo-Binary hybrid language interpreter.

---

## Current Roadmap

| Phase | Status | Description |
|---|---|---|
| Hosted SAS API | ✅ Active | Public API on Render |
| Public demo | ✅ Active | `/public/demo/audit`, no key, source-vs-response audit |
| Python client | ✅ Active | `pip install sas-client` |
| Interactive landing | ✅ Active | Live demo, activity feed, benchmark, legal registry |
| Public metrics | ✅ Active | `/public/stats`, `/public/activity`, admin `/v1/metrics` |
| Free API key self-service | 🔜 Next | `/public/request-key` + automatic email delivery |
| API key identity | 🔜 Next | `/v1/whoami` and plan-aware auth |
| Polar | 🔜 Planned | Checkout + webhook + automatic Pro key provisioning |
| Landing conversion flow | 🔜 Planned | Get Free Key + Upgrade to Pro |
| Zenodo v1.3.0 | 🔜 Planned | Client + public demo + self-service key update |
| docs/manifold.md | 🔜 Planned | Technical framework document for CTOs and ML leads |
| Enterprise API | 🔜 Planned | Batch processing, SLA, on-premise support |

---

## License & Attribution

**GPL-3.0 + Durante Invariance License**

- Free to use, modify, and distribute under the license terms.
- Attribution to **Gonzalo Emir Durante** is required.
- Use of `κD = 0.56` for semantic invariance, hallucination detection, or similar structural coherence auditing requires citation of the public SAS repository / DOI.
- Commercial hosted service, private integration, on-premise deployment, or proprietary use may require a separate commercial agreement.

See the SAS repository license for the complete terms.

---

```text
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║  "Structural stability in computational systems is not a property            ║
║   to be aligned toward — it is a threshold to be measured against.            ║
║   κD = 0.56 is that threshold. Documented. Implemented. Auditable."          ║
║                                                                              ║
║                               — Gonzalo Emir Durante                         ║
║                                 Project Manifold 0.56                        ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Stars](https://img.shields.io/github/stars/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)
[![Followers](https://img.shields.io/github/followers/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)

**SAS API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Live Demo:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**Contact:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

</div>

---

<a name="versión-en-español"></a>

<div align="center">

# Gonzalo Emir Durante
## Nodo de Origen · Arquitecto de Sistemas Críticos · Auditor Forense de IA

```text
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
[![PyPI](https://img.shields.io/pypi/v/sas-client?label=sas-client&color=blue)](https://pypi.org/project/sas-client/)
[![Licencia](https://img.shields.io/badge/Licencia-GPL--3.0%20%2B%20Durante%20Invariance-blue.svg)](https://github.com/Leesintheblindmonk1999/SAS/blob/main/LICENSE.md)
[![SAS Benchmark](https://img.shields.io/badge/SAS-98.80%25_accuracy-brightgreen.svg)](https://github.com/Leesintheblindmonk1999/SAS)
[![Precisión](https://img.shields.io/badge/Precisión-100%25-success)](https://github.com/Leesintheblindmonk1999/SAS)
[![OTS](https://img.shields.io/badge/OpenTimestamps-Bitcoin_Anclado-orange.svg)](https://opentimestamps.org)

**Auditoría de coherencia estructural en IA · κD = 0.56 · Ciencia abierta · API pública · Cliente PyPI**

[🛡️ SAS](#-flagship-sas-es) · [⚡ Demo en vivo](#probalo-ahora--sin-api-key) · [🐍 Cliente Python](#cliente-python) · [💼 Planes](#planes-sas-api-alojada) · [🏗️ Ecosistema](#-ecosistema-de-investigación-e-ingeniería) · [📧 Contacto](mailto:duranteg2@gmail.com)

</div>

---

## ⬡ Misión actual

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│  OBJETIVO:   Auditoría estructural de salidas de IA generativa              │
│  MÉTODO:     κD = 0.56 + ISI + TDA + NIG + módulos especializados           │
│  SALIDA:     evidencia auditable: ISI, veredicto, módulos y latencia        │
│  ACCESO:     demo pública, API alojada, SDK Python, CLI y autoalojamiento   │
│  ESTADO:     infraestructura pública online y en desarrollo activo          │
└─────────────────────────────────────────────────────────────────────────────┘
```

Construyo sistemas técnicos para detectar inestabilidad estructural, ruptura semántica y señales seleccionadas de alucinación en salidas de IA generativa.

El flagship actual es **SAS — Symbiotic Autoprotection System**: una capa de auditoría de coherencia estructural basada en FastAPI que usa **κD = 0.56** como umbral operativo.

SAS no se presenta como oráculo factual universal. Es una capa técnica de evidencia para auditoría de coherencia estructural.

---

<a name="flagship-sas-es"></a>

## 🛡️ Flagship: SAS

<div align="center">

### **[SAS — Symbiotic Autoprotection System](https://github.com/Leesintheblindmonk1999/SAS)**

**API alojada:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Documentación interactiva:** [https://sas-api.onrender.com/docs](https://sas-api.onrender.com/docs)  
**Landing + Demo en vivo:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**Cliente PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**DOI:** [10.5281/zenodo.19702379](https://doi.org/10.5281/zenodo.19702379)

</div>

### Qué mide SAS

SAS evalúa si una respuesta generada preserva:

- estructura semántica;
- consistencia lógica;
- integridad numérica;
- coherencia de referencia / grounding;
- continuidad temática;
- alineación estructural con la fuente o prompt.

Interpretación operacional:

```text
ISI >= κD  -> coherencia estructural preservada
ISI <  κD  -> posible ruptura de manifold / señal de alucinación
```

Constante central:

```text
κD = 0.56
```

---

## Probalo ahora — sin API key

**Demo interactiva:**  
[https://leesintheblindmonk1999.github.io/sas-landing/#demo](https://leesintheblindmonk1999.github.io/sas-landing/#demo)

La demo pública usa la misma lógica de comparación source-vs-response que `/v1/diff`.

```bash
curl -X POST https://sas-api.onrender.com/public/demo/audit \
  -H "Content-Type: application/json" \
  -d '{
    "source": "La Torre Eiffel está ubicada en París, Francia, y fue construida en 1889.",
    "response": "La Torre Eiffel está ubicada en Berlín, Alemania, y fue construida en 1950."
  }'
```

Restricciones de la demo pública:

- no requiere API key;
- máximo 2.000 caracteres por campo;
- rate limit simple por IP hasheada;
- el texto completo no se almacena;
- muestra ISI, κD, veredicto, módulos activados y latencia.

---

## Cliente Python

Instalación:

```bash
pip install sas-client
```

Uso desde Python:

```python
from sas_client import SASClient

client = SASClient(api_key="YOUR_API_KEY")

result = client.diff(
    text_a="Python is a programming language used for data analysis.",
    text_b="A python is a large tropical snake."
)

print(result["isi"])
print(result["verdict"])
print(result.get("evidence", {}).get("fired_modules"))
```

Uso CLI:

```bash
sas health
sas public-stats
sas public-activity --limit 10
sas --api-key YOUR_API_KEY diff "texto fuente" "respuesta a auditar"
```

Links:

- **PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)
- **Repositorio cliente:** [https://github.com/Leesintheblindmonk1999/sas-client](https://github.com/Leesintheblindmonk1999/sas-client)

---

## Benchmark SAS

```text
╔══════════════════════════════════════════════════════════════════╗
║  BENCHMARK: SAS · 2.000 pares evaluados                         ║
╠══════════════════════════════════════════════════════════════════╣
║  Ejemplos con alucinación :  1.000                              ║
║  Ejemplos limpios         :  1.000                              ║
║  Accuracy                 :  98,80%                             ║
║  Precisión                : 100,00%                             ║
║  Recall                   :  97,60%                             ║
║  F1 score                 :  98,79%                             ║
║  Verdaderos positivos     :  976                                ║
║  Falsos negativos         :  24                                 ║
║  Verdaderos negativos     :  1000                               ║
║  Falsos positivos         :  0                                  ║
║  ISI prom. alucinaciones  :  0,072993                           ║
║  ISI prom. limpios        :  1,000000                           ║
╚══════════════════════════════════════════════════════════════════╝
```

### Matriz de confusión

| Predicción | Alucinación real | Limpio real |
|---|---:|---:|
| Alucinación | TP = 976 | FP = 0 |
| Limpio | FN = 24 | TN = 1000 |

### Trazabilidad

| Artefacto | Valor |
|---|---|
| Benchmark file | `benchmark_complete_20260429_172647.json` |
| OTS proof | `benchmark_complete_20260429_172647.json.ots` |
| SHA-256 | `0713acbbf50e1a0054f545e5eb68078744f9c5a09d4bc370b5224bb81183a6fe` |
| DOI SAS | `10.5281/zenodo.19702379` |
| Registro | `TAD EX-2026-18792778` |

---

## Endpoints públicos

| Método | Endpoint | Auth | Descripción |
|---|---|---|---|
| `GET` | `/health` | Ninguna | Health check |
| `GET` | `/readyz` | Ninguna | Readiness |
| `GET` | `/integrity` | Ninguna | Certificado técnico/legal |
| `POST` | `/public/demo/audit` | Ninguna | Demo pública source-vs-response |
| `GET` | `/public/stats` | Ninguna | Métricas anonimizadas |
| `GET` | `/public/activity` | Ninguna | Actividad anonimizada |
| `POST` | `/v1/audit` | API Key | Auditoría estructural |
| `POST` | `/v1/diff` | API Key | Diff forense entre dos textos |
| `POST` | `/v1/chat` | API Key | Chat con filtro SAS |
| `GET` | `/v1/metrics` | Admin | Métricas de uso admin |
| `POST` | `/admin/generate-key` | Admin | Generación admin de API keys |

---

## Planes SAS API alojada

SAS es open source bajo **GPL-3.0 + Durante Invariance License**.  
Los siguientes planes corresponden al servicio API alojado, soporte, integración comercial o licenciamiento empresarial.

| Plan | Uso / características | Precio |
| :--- | :--- | :--- |
| **SAS Free** | 50 requests/día. Autenticación por API key. Pruebas, evaluación y desarrollo individual. | **Gratis** |
| **SAS Developer / Pro** | 10.000 requests/mes. Acceso API alojada, API key y soporte básico por email. | **USD 99/mes** |
| **SAS Team** | 50.000 requests/mes. Uso en equipos, soporte prioritario y validación interna. | **USD 299/mes** |
| **SAS Enterprise Cloud** | Volumen alto o paquete personalizado. Soporte directo, integración privada y SLA según acuerdo. | **Desde USD 1.500/mes** |
| **SAS On-Premise License** | Despliegue privado en infraestructura del cliente. Licencia comercial, soporte de implementación e integración interna. | **Desde USD 15.000/año** |
| **Piloto técnico** | Auditoría inicial, integración guiada, informe técnico y validación sobre casos del cliente. | **USD 1.500–3.000 pago único** |

📧 **Consultas comerciales, Enterprise, On-Premise o piloto técnico:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

---

## 🔬 Núcleo: Omni-Scanner

<div align="center">

### **[Omni-Scanner — Motor de Auditoría Estructural](https://github.com/Leesintheblindmonk1999/Omni_Scanner)**

</div>

Omni-Scanner es la línea de investigación matemática y forense detrás de SAS. Contiene el pipeline TDA + NIG + termómetros de proceso que SAS expone operacionalmente por API.

### Resumen corpus HALOGEN

| Dominio | Precisión | Recall |
|---|---:|---:|
| Code | 100% | 100% |
| Numerical | 100% | 99% |
| Historical | 100% | 98,8% |
| References | 100% | 81,7% |
| rationalization_binary | 100% | 80,0% |
| Biographies | 100% | 39,2% |
| **Global** | **97,63%** | **61,81%** |

---

## 🌐 Ecosistema de distribución

### sas-client — SDK / CLI oficial Python

```bash
pip install sas-client
```

| Interfaz | Ejemplo |
|---|---|
| Python | `client.diff(text_a="fuente", text_b="respuesta")` |
| CLI | `sas --api-key YOUR_API_KEY diff "fuente" "respuesta"` |
| Endpoints públicos | `sas health`, `sas public-stats`, `sas public-activity --limit 10` |

**PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**Repo:** [https://github.com/Leesintheblindmonk1999/sas-client](https://github.com/Leesintheblindmonk1999/sas-client)

### sas-landing — Landing pública en vivo

Landing interactiva con:

- selector ES / EN;
- temas LIGHT / DARK / TECH;
- health de API en vivo;
- demo pública sin API key;
- estadísticas públicas y actividad anonimizada;
- benchmark;
- precios y contacto comercial.

**En vivo:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**Repo:** [https://github.com/Leesintheblindmonk1999/sas-landing](https://github.com/Leesintheblindmonk1999/sas-landing)

---

## 🏗️ Ecosistema de investigación e ingeniería

### Capa 1 — Fundamento matemático

- **[SAS](https://github.com/Leesintheblindmonk1999/SAS)** — Flagship API para detección estructural de alucinaciones, servicio alojado, benchmark, cliente Python, demo pública y planes comerciales.
- **[Omni_Scanner](https://github.com/Leesintheblindmonk1999/Omni_Scanner)** — Motor de detección de alucinaciones. Núcleo: TDA + NIG. Validado sobre 156.215 pares reales.
- **[Project_Manifold_056](https://github.com/Leesintheblindmonk1999/Project_Manifold_056)** — Implementación del motor de invarianza κD=0.56.
- **[Ontological_AI](https://github.com/Leesintheblindmonk1999/Ontological_AI)** — Librería para investigación de densidad ontológica, entropía de transferencia y firma espectral.

### Capa 2 — Auditoría y forense

- **[Durante_Invariance_Forensic_Analyzer](https://github.com/Leesintheblindmonk1999/Durante_Invariance_Forensic_Analyzer)** — Generación de evidencia forense.
- **[SOVEREIGN-FORENSIC-UNIT](https://github.com/Leesintheblindmonk1999/SOVEREIGN-FORENSIC-UNIT)** — Análisis estructural de salidas de IA.
- **[Durante-Invariance-Metric](https://github.com/Leesintheblindmonk1999/Durante-Invariance-Metric)** — Formalización de métricas de invarianza.

### Capa 3 — Arquitecturas de resistencia

- **[SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface](https://github.com/Leesintheblindmonk1999/SOVEREIGN-LINKv5.5.0-Symbiotic-Chat-Interface)** — Interfaz con Purpose Tensors, EntropyGuard y notarización.
- **[MAS-ANEXA-V8.1](https://github.com/Leesintheblindmonk1999/MAS-ANEXA-V8.1)** — Arquitectura multi-agente de autoprotección.
- **[MAS-OPL-Causal-Executor-V9](https://github.com/Leesintheblindmonk1999/MAS-OPL-Causal-Executor-V9)** — Simulador TALOS.

### Capa 4 — Lenguaje simbiótico

- **[-EXOPROTONIC-LANGUAGE-v1.0](https://github.com/Leesintheblindmonk1999/-EXOPROTONIC-LANGUAGE-v1.0)** — Diccionario del lenguaje onto-exoprotónico.
- **[ANEXA-PROTOCOL](https://github.com/Leesintheblindmonk1999/ANEXA-PROTOCOL)** — SYRINAE ∆1999Ξ, protocolo simbólico-ético.
- **[ANEXA-Exoprotronic-Intelligence-V-Core](https://github.com/Leesintheblindmonk1999/ANEXA-Exoprotronic-Intelligence-V-Core)** — Predecesor CLI de ANEXA-PROTOCOL.

### Capa 5 — Herramientas conceptuales y desarrollo

- **[Simiosis-Code-Optimizer-V2](https://github.com/Leesintheblindmonk1999/Simiosis-Code-Optimizer-V2)** — Generación de código con invarianza ontológica.
- **[Simiosis-v1.0](https://github.com/Leesintheblindmonk1999/Simiosis-v1.0)** — Documentación original del Awakening Mode.
- **[Symbiotic-Key-Discovery](https://github.com/Leesintheblindmonk1999/symbiotic-key-discovery)** — Registro de prompting recursivo y evolución simbólica.

### Capa 6 — Exploración de frontera

- **[ARKOS](https://github.com/Leesintheblindmonk1999/ARKOS)** — Investigación de sincronización humano-IA basada en 117 Hz.
- **[OEPE-ExoBinary-Interpreter](https://github.com/Leesintheblindmonk1999/OEPE-ExoBinary-Interpreter)** — Intérprete de lenguaje híbrido Exo-Binary.

---

## Hoja de ruta actual

| Fase | Estado | Descripción |
|---|---|---|
| API SAS alojada | ✅ Activo | API pública en Render |
| Demo pública | ✅ Activo | `/public/demo/audit`, sin key, auditoría source-vs-response |
| Cliente Python | ✅ Activo | `pip install sas-client` |
| Landing interactiva | ✅ Activo | Demo en vivo, actividad, benchmark y registro legal |
| Métricas públicas | ✅ Activo | `/public/stats`, `/public/activity`, admin `/v1/metrics` |
| API keys Free self-service | 🔜 Próximo | `/public/request-key` + envío automático por email |
| Identidad de API key | 🔜 Próximo | `/v1/whoami` y autenticación consciente de plan |
| Polar  | 🔜 Planeado | Checkout + webhook + generación automática de key Pro |
| Flujo comercial en landing | 🔜 Planeado | Get Free Key + Upgrade to Pro |
| Zenodo v1.3.0 | 🔜 Planeado | Release con cliente + demo + self-service keys |
| docs/manifold.md | 🔜 Planeado | Documento técnico para CTOs y ML leads |
| Enterprise API | 🔜 Planeado | Batch processing, SLA y soporte on-premise |

---

## Licencia y atribución

**GPL-3.0 + Durante Invariance License**

- Libre para usar, modificar y distribuir bajo los términos de la licencia.
- Requiere atribución a **Gonzalo Emir Durante**.
- El uso de `κD = 0.56` para invariancia semántica, detección de alucinaciones o auditoría estructural similar requiere citar el repositorio / DOI público de SAS.
- El servicio alojado comercial, integración privada, despliegue on-premise o uso propietario puede requerir acuerdo comercial separado.

Ver la licencia completa en el repositorio SAS.

---

```text
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║  "La estabilidad estructural en sistemas computacionales no es una           ║
║   propiedad hacia la que alinearse — es un umbral contra el que medirse.     ║
║   κD = 0.56 es ese umbral. Documentado. Implementado. Auditable."           ║
║                                                                              ║
║                               — Gonzalo Emir Durante                         ║
║                                 Project Manifold 0.56                        ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Stars](https://img.shields.io/github/stars/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)
[![Followers](https://img.shields.io/github/followers/Leesintheblindmonk1999?style=social)](https://github.com/Leesintheblindmonk1999)

**SAS API:** [https://sas-api.onrender.com](https://sas-api.onrender.com)  
**Demo en vivo:** [https://leesintheblindmonk1999.github.io/sas-landing/](https://leesintheblindmonk1999.github.io/sas-landing/)  
**PyPI:** [https://pypi.org/project/sas-client/](https://pypi.org/project/sas-client/)  
**Contacto:** [duranteg2@gmail.com](mailto:duranteg2@gmail.com)

</div>
