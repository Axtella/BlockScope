```
BlockScope/
├── api/
│   ├── __init__.py
│   ├── routes/
│   │   ├── __init__.py
│   │   ├── analysis.py
│   │   ├── auth.py
│   │   ├── portfolio.py
│   │   └── websocket.py
│   ├── middleware/
│   │   ├── __init__.py
│   │   ├── auth.py
│   │   ├── rate_limit.py
│   │   └── logging.py
│   └── dependencies.py
├── core/
│   ├── __init__.py
│   ├── analysis/
│   │   ├── __init__.py
│   │   ├── trades.py
│   │   ├── patterns.py
│   │   ├── metrics.py
│   │   ├── portfolio.py
│   │   ├── risk.py
│   │   └── liquidity.py
│   ├── blockchain/
│   │   ├── __init__.py
│   │   ├── node.py
│   │   ├── data.py
│   │   ├── rpc.py
│   │   └── events.py
│   └── ml/
│       ├── __init__.py
│       ├── detection/
│       │   ├── __init__.py
│       │   ├── mev.py
│       │   ├── pump_dump.py
│       │   └── front_running.py
│       ├── models.py
│       └── training.py
├── cli/
│   ├── __init__.py
│   ├── commands/
│   │   ├── __init__.py
│   │   ├── analyze.py
│   │   ├── batch.py
│   │   └── config.py
│   ├── output/
│   │   ├── __init__.py
│   │   ├── formatters.py
│   │   ├── json.py
│   │   └── csv.py
│   └── visualization/
│       ├── __init__.py
│       └── charts.py
├── telegram/
│   ├── __init__.py
│   ├── bot.py
│   ├── handlers/
│   │   ├── __init__.py
│   │   ├── analysis.py
│   │   ├── alerts.py
│   │   └── tracking.py
│   └── notifications/
│       ├── __init__.py
│       └── alerts.py
├── database/
│   ├── __init__.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── wallet.py
│   │   ├── transaction.py
│   │   └── analysis.py
│   ├── migrations/
│   │   └── __init__.py
│   └── operations/
│       ├── __init__.py
│       ├── crud.py
│       └── queries.py
├── config/
│   ├── __init__.py
│   ├── settings.py
│   ├── logging.py
│   └── feature_flags.py
├── utils/
│   ├── __init__.py
│   ├── cache.py
│   ├── helpers.py
│   ├── decorators.py
│   └── metrics.py
├── tests/
│   ├── __init__.py
│   ├── conftest.py
│   ├── unit/
│   │   ├── __init__.py
│   │   ├── test_analysis.py
│   │   ├── test_blockchain.py
│   │   └── test_ml.py
│   └── integration/
│       ├── __init__.py
│       ├── test_api.py
│       └── test_database.py
├── docker/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   └── nginx/
│       └── nginx.conf
├── deployment/
│   ├── kubernetes/
│   │   ├── deployment.yaml
│   │   └── service.yaml
│   └── terraform/
│       └── main.tf
├── docs/
│   ├── api/
│   │   └── openapi.yaml
│   ├── architecture/
│   │   └── diagrams.md
│   └── setup.md
├── scripts/
│   ├── setup.sh
│   ├── setup.bat
│   └── deploy.sh
├── .env.example
├── .gitignore
├── main.py
├── pyproject.toml
├── README.md
└── requirements/
    ├── base.txt
    ├── dev.txt
    └── prod.txt
```

This expanded structure includes:

1. **New API Organization:**
   - Separated routes by functionality
   - Added middleware for auth, rate limiting
   - WebSocket support

2. **Enhanced Core Components:**
   - Expanded analysis capabilities
   - ML detection modules
   - RPC management

3. **Improved CLI Structure:**
   - Separated commands
   - Added visualization
   - Multiple output formats

4. **Extended Database Layer:**
   - Models organization
   - Migrations support
   - Separated operations

5. **Development Tools:**
   - Docker configuration
   - Kubernetes manifests
   - Terraform configs

6. **Documentation:**
   - API documentation
   - Architecture diagrams
   - Setup guides

7. **Testing Framework:**
   - Unit tests
   - Integration tests
   - Test configurations

