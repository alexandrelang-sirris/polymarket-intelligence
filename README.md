# polymarket-intelligence
Playground for Polymarket insights

## Repo Structure

polymarket-intelligence/
│
├── pipeline/
│   ├── fetch.py          # Polymarket API client
│   ├── features.py       # Feature engineering
│   ├── analysis.py       # ML / stats
│   ├── summarize.py      # GenAI / text output
│   ├── run.py            # Orchestrator
│
├── upload/
│   └── azure_blob.py     # Upload logic
│
├── schemas/
│   └── market.json       # Output contract
│
├── data/
│   └── samples/          # Cached dev data
│
├── requirements.txt
└── README.md
