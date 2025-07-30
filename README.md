# AWS---Shipping-Product
README – Freight Charges Optimization Project
Project Overview
This project leverages AWS technologies including Amazon Bedrock and Lambda to build an intelligent freight charge optimization system. The platform helps automate shipping decisions by integrating with carrier APIs (UPS, FedEx, DHL) to recommend cost-effective shipping options and provide streamlined support for filling out shipping documents such as the Bill of Lading.
Key Features
- 🔍 Carrier Price Comparison Agent: An AI agent powered by Amazon Bedrock that compares real-time rates across UPS, FedEx, DHL APIs to identify the most cost-effective shipping method.
- 🧠 AI Recommendations: Recommends optimal shipping models based on historical data and real-time carrier pricing.
- 📄 Bill of Lading Auto-Assist: Automatically fills out sections of the Bill of Lading form based on parsed input data and selected carrier info to reduce manual entry.
Technologies Used
- AWS Lambda - Amazon Bedrock Agents - Carrier APIs (UPS, FedEx, DHL) - Amazon S3 / DynamoDB for storage - API Gateway - Python / Node.js - Optional: React.js or QuickSight for dashboard
Setup Instructions
1. Clone the repository. 2. Set up AWS Lambda functions with proper IAM roles. 3. Configure Bedrock agent for inference and carrier rate comparison logic. 4. Connect carrier APIs and store API credentials securely in AWS Secrets Manager. 5. Deploy front-end dashboard or visualization tool (React.js or QuickSight). 6. Test end-to-end shipping cost optimization and Bill of Lading generator.
Contributors
- Team Lead: [Insert Name] - Carrier API Integration: [Insert Name] - AI Agent Development: [Insert Name] - Bill of Lading Automation: [Insert Name] - Dashboard/Frontend: [Insert Name]
