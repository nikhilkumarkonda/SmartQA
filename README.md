# SmartQA – Quality Engineering Workspace

**Version 2 | Generative AI + Rule-Based Testing Tools**

SmartQA is an AI-powered quality engineering portfolio project designed to assist QA professionals with test design, test case review, coverage analysis, and execution status reporting.

## Key Features

- **Intelligent Test Case Generation:** Generate structured test scenarios and expected results from requirements and user stories.
- **Semantic Duplicate Detection:** Identify potentially overlapping test scenarios based on their meaning and intent.
- **Coverage Gap Analysis:** Analyze existing test scenarios against requirements and suggest missing coverage.
- **QA Status Reporting:** Generate professional QA summaries using execution metrics and supplied risk information.
- **Export Capabilities:** Download generated test cases in CSV format and AI reports in text format.
- **Dual Processing Modes:** Switch between Gemini-powered analysis and rule-based testing tools.

## Technology Stack

- Python
- Streamlit
- Google Gemini API
- REST API integration
- Git and GitHub

## Security and Responsible AI

- API credentials are retrieved through environment variables.
- Input validation and structured output checks are implemented.
- API error handling and retry mechanisms are included.
- Only fictional, non-confidential data should be used.
- AI-generated results require human QA validation.

## Run Locally

Install dependencies:

`pip install -r requirements.txt`

Configure the `GEMINI_API_KEY` environment variable securely.

Launch the application:

`streamlit run app.py`

## Deployment

Designed for deployment through Streamlit Community Cloud with securely configured application secrets.

## Limitations

SmartQA is a portfolio demonstration, not a production-certified testing platform. AI responses may contain inaccuracies. API availability and usage are subject to provider limits.

The application does not execute actual tests, connect to enterprise test management systems, or provide automated