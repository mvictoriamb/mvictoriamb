# mvictoriamb
**3rd-Year Cybersecurity & AI Undergraduate**

Security Engineering · Threat Intelligence · Applied Machine Learning · AI-Assisted Investigation

[Email](mailto:mvictoriamb0425@gmail.com) · [Repositories](https://github.com/mvictoriamb?tab=repositories)

## Cybersecurity and Security Engineering

### [Asynchronous Threat Analysis Engine](https://github.com/mvictoriamb/async-threat-analysis-engine)

**FastAPI · Celery · Redis · PostgreSQL · Docker · VirusTotal API · Streamlit**

A threat-intelligence pipeline that processes domain analysis in background workers and presents results through an analyst dashboard.

- Separates API requests from external lookups using queued Celery tasks and Redis.
- Combines VirusTotal verdicts with lexical domain heuristics, including entropy and character distribution.
- Persists scan records and JSON telemetry in PostgreSQL for investigation and review.

### [GNS3 Enterprise Security Labs](https://github.com/mvictoriamb/gns3-security-labs-mvmb)

**GNS3 · Snort IDS · pfSense · OpenVPN · Linux iptables · Nmap**

Documented network security exercises covering attack simulation, monitoring and defensive configuration in controlled virtual environments.

- Investigates SYN floods, ARP spoofing, brute-force attempts and network reconnaissance.
- Configures IDS monitoring, firewall rules, VPN access and port knocking.
- Includes lab reports describing configurations and observed behaviour.

## Security and Machine Learning in Development

### [AI Hybrid WAF and IPS](https://github.com/mvictoriamb/ai-hybrid-waf-ips)

**Python · scikit-learn · Random Forest · CIC-IDS2017**

A project exploring machine-learning-based traffic classification and its integration with defensive tooling for small business environments.

- **Implemented milestone:** data preparation and Random Forest training on CIC-IDS2017.
- **Planned integration:** Scapy traffic capture, Linux firewall mitigation, a Flask honeypot and local LLM incident summaries through Ollama.

### [Sentinel — Security Triage and Investigation](https://github.com/mvictoriamb/sentinel-vertex-secops)

**Python · Pydantic · Security Telemetry · Planned Vertex AI and Gemini Integration**

An early-stage SecOps project focused on decision-time data integrity and constrained AI-assisted investigation of Windows endpoint alerts.

- **Implemented milestone:** telemetry and investigation-episode data contracts, with validation tests.
- **Planned work:** episode construction, calibrated ML prioritization, Vertex AI deployment and a bounded Gemini investigation agent with read-only tools and evidence-linked reports.

## Applied AI and Data Tools

### [SANA — Smart Assistant and Notification Agent](https://github.com/mvictoriamb/SANA_asistente)

**Python · Google Gemini · Gmail API · Google Calendar API · OAuth 2.0 · Speech Recognition · Edge TTS**

A voice-oriented assistant for reviewing email and calendar information across connected accounts.

- Summarizes email threads and retrieves upcoming calendar events.
- Integrates speech recognition and text-to-speech with Google API services.
- Uses OAuth 2.0 for account authorization.

### [AI Data Explorer](https://github.com/mvictoriamb/analizador_datos_inteligente)

**Python · pandas · PandasAI · OpenAI · Matplotlib · Seaborn**

A data exploration project combining conventional statistical analysis with natural-language queries over a student employability dataset.

- Includes a baseline analysis notebook and an AI-assisted query script.
- Explores descriptive statistics, correlations and visualizations through Python and natural-language interaction.

## Other Research

### [AML Biomarker Discovery and Bioelectric Simulation](https://github.com/mvictoriamb/AML-Bioelectric-CRISPRa-Simulation)

**Python · TensorFlow/Keras · Statistical Analysis · RNA-seq · PhysiCell/C++**

An interdisciplinary research project combining expression-based biomarker exploration, a classification workflow and hypothetical cellular simulations.

- Includes external CREB5–KCNJ15 coexpression replication in TCGA-LAML and Beat AML, with analysis scripts and source provenance.
- Provides recovered PhysiCell settings and a documented C++ reconstruction.
- Separates association findings from predictive model validation and therapeutic claims.

[External RNA-seq analysis and reproducibility](https://github.com/mvictoriamb/AML-Bioelectric-CRISPRa-Simulation/tree/main/validation/external_rnaseq)
