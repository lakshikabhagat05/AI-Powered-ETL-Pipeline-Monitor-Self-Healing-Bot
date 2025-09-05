# AI-Powered-ETL-Pipeline-Monitor-Self-Healing-Bot
project that demonstrates ETL orchestration, data validation, monitoring with an Agentic AI (LangChain), and a lightweight dashboard.. This project uses free components: Python, MySQL, Apache Airflow, Streamlit, LangChain (open-source). For LLM usage the example uses OpenAI.

## Features
- Orchestrate ETL using Apache Airflow DAG.
- Log job runs and statuses to a local JSON log (and optionally to MySQL).
- LangChain-based monitoring agent that inspects logs and suggests or executes simple self-healing actions.
- Streamlit dashboard to view pipeline health and AI insights.
- Slack webhook alerts for failures requiring manual attention.


## Tech stack
- Python 3.9+
- Apache Airflow (local)
- MySQL (or MariaDB)
- LangChain
- Streamlit
