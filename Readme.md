# Multi-agent Customer Support Automation for Kerala Tourism

## Overview

This project implements an advanced multi-agent customer support automation system specifically designed for Kerala Tourism. Using the crewAI framework, it leverages two AI agents to provide efficient, personalized, and high-quality customer support:

1. Senior Support Representative: Handles direct customer inquiries, providing comprehensive and friendly responses.
2. Support Quality Assurance Specialist: Reviews and refines the support representative's responses to ensure accuracy, completeness, and adherence to quality standards.

The system uses natural language processing and machine learning to understand customer inquiries, access relevant tourism information, and generate appropriate responses. It's designed to scale support operations while maintaining a personal touch, crucial for the tourism industry.

## Introduction

This multi-agent customer support system aims to resolve customer issues quickly and efficiently. The Senior Support Representative agent addresses customer inquiries promptly, while the Quality Assurance Specialist monitors interactions to improve performance and ensure adherence to support protocols. This setup delivers efficient and personalized support at scale, enhancing the overall customer experience for Kerala Tourism.

## Requirements

- Python 3.7 or higher
- crewAI library
- OpenAI API key


## Installation

1. Clone the repository:

```
git clone https://github.com/muneebth/Multi-agent_Customer_Support_Automation.git
```

2. Set your OpenAI API key as an environment variable:

```
export OPENAI_API_KEY="your-api-key-here"
```


## Components

- **Agents**: 
  - Senior Support Representative
  - Support Quality Assurance Specialist

- **Tasks**:
  - Inquiry Resolution
  - Quality Assurance Review

- **Tools**:
  - Web Scraping Tool (for Kerala tourism information)

## Customization

You can modify the `inputs` dictionary in the script to process different customer inquiries:

```python
inputs = {
 "customer": "Customer Name",
 "person": "Contact Person",
 "inquiry": "Customer's question or request"
}```

