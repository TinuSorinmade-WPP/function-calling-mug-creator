# AI-Powered Custom Mug Generator

## Project Overview

This project creates personalized mugs using AI-generated poems through the Azure Open AI API and Zazzle's customization platform. It automatically generates a unique poem based on an event name and creates a custom Zazzle link for mug creation.

## Features

- AI poem/rap generation using GPT-4
- Automatic Zazzle link creation for custom mugs
- Event-specific personalization
- Character-limited poems (130 characters) for optimal mug design

## Prerequisites

- Azure OpenAI API access
- Python 3.x
- Valid Azure API credentials

## Installation

1. Clone the repository:

```bash
git clone [repository-url]
```

2. Install required packages in virtual environment)

```bash
pip install openai requests
```

3. Set up environment variables (in your command prompt)

```bash
set AZURE_KEY="your-azure-api-key"
set AZURE_ENDPOINT="your-azure-endpoint"
```

