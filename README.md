# Intent-Based 5G Network Optimizer with LLM

Autonomous 5G RAN optimization driven by natural language intent, using a Groq-powered LLM pipeline and six specialized AI agents.

## Overview

Traditional RAN management requires operators to manually translate business goals into low-level network parameters. This system eliminates that gap entirely:

> An operator types: *"Prioritize emergency communications at the hospital now"*  
> Six AI agents process the intent, configure the network, and report back.

Built on 3GPP Release 18 principles with a working Groq LLM backbone.

## Agent Pipeline

| Agent | Role |
|-------|------|
| Intent Agent | Parses and validates natural language intent |
| Planner Agent | Maps intent to network action plan |
| Optimizer Agent | Computes optimal RAN parameters |
| Monitor Agent | Tracks KPIs and detects anomalies |
| LLM Client | Interfaces with Groq API for reasoning |
| Crew Coordinator | Orchestrates agent execution order |

## Features

- Natural language interface for network configuration
- Real-time KPI monitoring and anomaly detection
- Autonomous self-healing with fault recovery
- 6G HetNet dataset integration for realistic simulation
- Full project documentation and deployment guide

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3.11 |
| LLM | Groq (Llama 3) |
| Agent Framework | CrewAI |
| Network Data | 6G HetNet Transmission Management CSV |
| Configuration | Pydantic |

## Getting Started

```bash
git clone https://github.com/DAleid/Intent-Based-5G-Network-Optimizer-with-LLM.git
cd Intent-Based-5G-Network-Optimizer-with-LLM
pip install -r requirements.txt
cp .env.example .env    # Add GROQ_API_KEY
python app.py
```

To test the Groq connection:

```bash
python test_groq.py
```

## Documentation

- [Project Documentation](PROJECT_DOCUMENTATION.md)
- [Project Report](PROJECT_REPORT.md)

## License

MIT License