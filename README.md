# FraudDetectionInBankingSystem

Use Case: A banking system that analyzes transactions and sends alerts for suspicious activity to multiple departments (e.g., fraud detection, compliance, customer support).<br>
<br>
How Topics Help:<br>
Publish transaction data to a topic.<br>
Subscribers filter messages based on fraud detection rules:<br>
Fraud detection team receives messages with Amount > 10000 AND Country != 'HomeCountry'.<br>
Compliance team receives messages with TransactionType = 'HighRisk'.<br>
Send Email to customer regarding fraud transaction.<br>
<br>
Azure Services:<br>
  &nbsp;&nbsp;1)Service Bus Topics for transaction analysis.<br>
  &nbsp;&nbsp;2)Azure Functions for processing messages.<br>
