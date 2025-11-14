# langchain-tools
This directory will contain scripts and tools that will be used to learn langchain and python (including related tools for each). Scripts will generally be contained in a single source file.

## Runtime & Language
- **Python**: 3.12+

## Package Management
- **Package Manager**: uv
- **Config**: pyproject.toml
- **Lock file**: uv.lock

## Key Dependencies
- **langchain[anthropic]** (>=1.0.5) - LangChain framework with Anthropic/Claude integration
- **python-dotenv** (>=1.2.1) - Environment variable management

### Environment Configuration
- Create `.env` file with required API keys (e.g., ANTHROPIC_API_KEY)

### Run
There will be many different applications but they will all be run in the same fashion as described below:
```bash
# Run the application
uv run main.py

# Or with activated environment (source .venv/bin/activate)
python main.py
```

## Application Type
LangChain agent applications using Claude Sonnet 4.5
