# FISCal Architecture

## Pipeline
Document → Processing Specialist → Fraud Analyst → Compliance Officer

## Components
- **src/agents/** - AI agent definitions
- **src/document_processing/** - LandingAI integration
- **src/config/** - Settings
- **src/dashboard/** - Streamlit UI

## Tech Stack
- LandingAI ADE for document extraction
- CrewAI for agent workflows
- AWS Bedrock for LLM
- Streamlit for UI
