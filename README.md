# Team-Spark
# ChargeWise AI

## Overview
ChargeWise AI is an AI-powered platform that recommends optimal locations for EV charging stations using location intelligence and cloud-based analytics.

## Problem Statement
As EV adoption grows, charging infrastructure must be strategically deployed. Poor placement leads to low utilization, increased costs, and poor user experience.

## Solution
ChargeWise AI analyzes key location factors such as population density, traffic density, commercial activity, and existing charging infrastructure to recommend the best locations for new EV charging stations.

## Architecture

- Amazon S3 – Data storage
- AWS Lambda – Recommendation engine
- Amazon API Gateway – API endpoint
- Frontend Dashboard – Visualization layer
## Architecture diagram
https://github.com/Goodness4life/Team-Spark/blob/main/DOC-20260606-WA0062..pdf
## SOW
https://github.com/Goodness4life/Team-Spark/blob/main/Team%20Spark%20SOW.pdf
Sample response 
[
  {
    "location": "Lekki",
    "score": 92,
    "rank": 1
  },
  {
    "location": "Ikeja",
    "score": 88,
    "rank": 2
  }
]

Project structure
chargewise-ai/
├── frontend/
├── backend/
├── architecture/
├── datasets/
└── docs/

## Business impact 
•Improves EV charging station placement 
• Reduce infrastructure development cost
• Support sustainable transition growth
• Enables data decision making
## Future Enhancement 
• Realtime traffic integration 
• Machine learning prediction models 
• Geographic heat map 
• Live EV demand forecasting 

## Team members 
• Goodness Adepoju
• Favour Alfred

## AWS Services Used

- Amazon S3
- AWS Lambda
- Amazon API Gateway


## API Endpoint
https://06nwru8m2b.execute-api.us-east-1.amazonaws.com/pod/recommendations
## Demo
http://localhost:5173
