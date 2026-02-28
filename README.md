# Serverless-Order-Processing-CSP451
CSP451 Week 9 – Serverless Order Processing using Azure Service Bus and Logic App
# Serverless Order Processing System – CSP451 Week 9

## Project Overview
This project demonstrates a serverless, event-driven order processing system built using Microsoft Azure services.

## Architecture
Client → Azure Service Bus → Azure Logic App → Database → Email Notification

## Azure Services Used
- Azure Service Bus (order-queue)
- Azure Logic App
- Azure Cosmos DB / Azure Table Storage
- Outlook Email (Notification)

## Workflow
1. Order message is sent directly to Azure Service Bus queue.
2. Logic App is triggered when a new message arrives.
3. Logic App processes the order.
4. Order is stored in the database.
5. Confirmation email is sent automatically.

## Key Concepts Demonstrated
- Event-driven architecture
- Asynchronous message processing
- Serverless workflow automation
- Cloud-based database storage
