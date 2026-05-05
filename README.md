# CBA Operations AI Assistant

An AI-powered customer service assistant for Commonwealth Bank's Chief Operations Office (COO), combining Machine Learning, Generative AI, and Agentic AI to reimagine the customer service experience.

## Project Structure

cb-ai/
├── src/cb_ai/       # Main Python package
├── tests/           # Test suite
├── data/            # Local sample data (never commit real data)
├── notebooks/       # Experimentation notebooks
├── docs/            # Documentation
└── .github/         # CI/CD workflows

## Prerequisites

- Python 3.14+
- [uv](https://docs.astral.sh/uv/) package manager

## Setup

# Clone the repo
git clone https://github.com/sharmaanix/CB-AI.git
cd CB-AI

# Install dependencies
uv sync

## Running Tests

uv run pytest

## Environment Variables

Copy .env.example to .env and fill in the values:

cp .env.example .env

| Variable | Description |
|---|---|
| OPENAI_API_KEY | API key for LLM provider |
| AWS_REGION | AWS region for cloud services |