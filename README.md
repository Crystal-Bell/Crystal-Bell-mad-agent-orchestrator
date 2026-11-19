mad-agent-orchestrator/
├── .github/
│   └── workflows/
│       └── daily-agent-sync.yml    # Cloud scheduler & auto-commit runner
├── scripts/
│   └── sync_agent.py               # RSS scraper + Gemini API processor
├── config/
│   └── feeds.txt                   # List of RSS & supply-chain feed URLs
├── briefs/                         # Auto-generated daily global debriefs
└── staged_readmes/                 # Auto-formatted YAML + Mermaid READMEs
# Crystal-Bell-mad-agent-orchestrator
sync_agent.py
