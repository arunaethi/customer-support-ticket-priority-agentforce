# Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce

## Project Overview

This project is designed to automate customer support ticket prioritization and assignment using Salesforce Flow and Agentforce.

The system analyzes the customer support ticket description and determines whether the ticket is High, Medium, or Low priority. High-priority tickets trigger automated task creation for urgent handling.

## Problem Statement

Manual ticket prioritization and assignment can cause delays in resolving urgent customer issues. This project aims to automate ticket analysis, priority classification, and support task creation.

## Objectives

- Automatically analyze support ticket descriptions
- Classify tickets into High, Medium, or Low priority
- Identify urgent customer issues
- Automatically create a task for high-priority tickets
- Reduce manual effort
- Improve support response time

## Technologies Used

- Salesforce
- Salesforce Custom Objects
- Salesforce Flow
- Agentforce
- GitHub

## Salesforce Implementation

### Custom Object

Support Ticket Intelligence

### Important Fields

- Ticket Number
- Customer
- Contact
- Issue Type
- Description
- Priority Level
- Status
- Created Date
- Assigned To
- SLA Breach Risk
- Resolution Time

## Automation Flow

The Auto-Launched Flow performs the following operations:

1. Accepts the customer account name
2. Retrieves the customer account
3. Retrieves the latest support ticket
4. Analyzes the ticket description
5. Determines ticket priority
6. Creates an urgent task for High-priority tickets
7. Assigns the appropriate support level
8. Returns the final action message

## Priority Logic

### High Priority
Keywords:
- urgent
- not working
- failure

### Medium Priority
Keywords:
- issue
- slow
- delay

### Low Priority

Tickets that do not match the High or Medium priority conditions are classified as Low priority.

## Current Implementation Status

- Custom Object: Completed
- Custom Fields: Completed
- Sample Support Ticket: Completed
- Auto-Launched Flow: Completed
- Priority Classification: Completed
- High-Priority Task Automation: Completed
- Flow Testing: Completed
- Agentforce Integration: In Progress

## Expected Outcomes

- Faster identification of urgent tickets
- Reduced manual ticket handling
- Improved support workflow
- Better prioritization of customer issues
- Improved team productivity

## Future Enhancement

Agentforce will be integrated with the completed Flow to allow users to analyze support tickets through a conversational interface and trigger the backend automation.

## Project Status

Salesforce Flow implementation completed successfully. Agentforce integration is being completed separately.

