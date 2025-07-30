# FraudDetectionInBankingSystem

Use Case: A banking system that analyzes transactions and sends alerts for suspicious activity to multiple departments (e.g., fraud detection, compliance, customer support).
How Topics Help:
Publish transaction data to a topic.
Subscribers filter messages based on fraud detection rules:
Fraud detection team receives messages with Amount > 10000 AND Country != 'HomeCountry'.
Compliance team receives messages with TransactionType = 'HighRisk'.
Send Email to customer regarding fraud transaction.
Azure Services:
  Service Bus Topics for transaction analysis.
  Azure Functions for processing messages.
