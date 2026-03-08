# AI Smart HR Assistant (Amazon Bedrock)

## Project Overview
This project demonstrates how to build an AI-powered HR assistant using Amazon Bedrock Agents and Knowledge Bases.

The assistant helps employees:
- Ask questions about HR policies
- Retrieve company benefits information
- Submit benefit claims

## Architecture

[architecture diagram]

## Technologies Used

- Amazon Bedrock
- Bedrock Agents
- Bedrock Knowledge Base
- Amazon OpenSearch Serverless
- AWS Lambda
- Amazon DynamoDB
- Amazon S3

## Project Workflow

1. User asks HR question
2. Bedrock Agent interprets request
3. Knowledge Base retrieves HR documents
4. Agent generates response
5. If action required → Lambda invoked
6. Claim stored in DynamoDB

## Repository Structure

project folders explanation
ai-smart-hr-assistant-aws-bedrock
│
├── README.md
├── architecture
│   └── architecture-diagram.png
│
├── screenshots
│
├── knowledge-base-data
│   └── hr-benefits-policy.pdf
│
├── prompts
│   └── agent-instructions.txt
│
└── docs
    ├── project-overview.md
    ├── setup-guide.md
    └── testing-guide.md

## Setup Instructions

Step 1 – Create S3 bucket  
Step 2 – Upload HR documents  
Step 3 – Create Bedrock Knowledge Base  
Step 4 – Configure OpenSearch Vector Store  
Step 5 – Create Bedrock Agent  
Step 6 – Attach Knowledge Base  
Step 7 – Add Action Group  
Step 8 – Deploy Lambda function  
Step 9 – Test agent

## Screenshots

## Future Improvements

Add authentication  
Integrate Slack / Teams  
Add more HR automation

## Author

Suvo Biswas
