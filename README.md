# SmartQA — Quality Engineering Workspace

Interactive rule-based QA portfolio prototype built with Python and Streamlit.

## Run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

## Features
- Scenario suggestions for login, shopping cart, and password reset
- Basic duplicate detection for pasted test cases
- Keyword-based category coverage checks
- CSV download of suggested test cases

## Important limitations
This is **not yet a generative-AI application**. It uses fixed scenario templates and keyword rules, and cannot reliably analyze arbitrary requirements. Never enter confidential workplace information. All suggested tests must be validated by a human tester.

## Deployment
Create a GitHub repository containing `app.py` and `requirements.txt`, then deploy it through Streamlit Community Cloud. Select `app.py` as the entrypoint. Public availability and hosting eligibility depend on the hosting provider.
