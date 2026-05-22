# Paul Mirzayantz

> *The how and the why are the interesting parts. The fix is just the conclusion.*

🟢 **Open to work** — AI engineering · systems · cybersecurity

---

I build things that work in constrained environments.  
AI/ML · cybersecurity · edge computing · systems that shouldn't need the cloud.  
RNCP Level 6 — AI & Big Data Engineering. Bilingual FR/EN.

---

## Projects

### 🔍 Autonomous Pentesting Agent
Agentic pipeline that decides which attack surfaces to probe — no human input.  
Nmap → fine-tuned Llama 3 8B → OWASP ZAP against a live DVWA cyber range.  
Debugged a silent Docker networking issue where ZAP was scanning itself: three independent root causes, one symptom. Passive scan went from silence to a full vulnerability report.

`llm` `llama3` `owasp-zap` `nmap` `docker` `cybersecurity`

---

### 🛡️ ML Intrusion Detection System
Deep neural network trained on CICIDS2017 (78 features/flow) — **91% attack detection accuracy**.  
Original plan hit a wall when CICFlowMeter proved deprecated and unbuildable. Pivoted from raw .pcap processing to a CSV inference pipeline. Delivered a Dockerized real-time Streamlit dashboard.  
Working solution over perfect solution.

`deep-learning` `keras` `tensorflow` `scikit-learn` `pandas` `numpy` `streamlit` `docker` `network-security`

---

### 🔊 PAVAD — Offline Voice Assistant
Full edge AI pipeline on a Raspberry Pi 5 — no cloud, no internet required.  
Vosk (STT) → Qwen2.5 1.5B Q4 via llama.cpp (LLM) → Piper (TTS).  
~1s STT · ~1.5s TTS on 4GB RAM. Roadmap includes LoRa mesh for off-grid emergency comms and a rugged physical enclosure.  
Built for environments where connectivity isn't guaranteed. *(demo available on request)*

`edge-ai` `raspberry-pi` `llama.cpp` `offline` `tts` `stt` `embedded`

---

## Stack

```
Python · PyTorch · Keras · TensorFlow · scikit-learn · pandas · numpy
HuggingFace · llama.cpp · Docker · FastAPI · Streamlit
Nmap · OWASP ZAP · SQLite · Raspberry Pi · Linux
```

---

## Contact

- 💼 [https://www.linkedin.com/in/paul-mirzayantz-73355833b/](#)
- 📧 [paulmirzayantz@protonmail.com](#)
