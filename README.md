AI-Driven Workflow Automation Architecture

This project demonstrates an end-to-end AI-powered workflow designed to optimise manual service request triage. It integrates LLM-based classification, confidence-driven routing logic, human-in-the-loop governance, and structured KPI logging to create a scalable and auditable operational system.

Incoming requests are automatically ingested, semantically classified, assigned priority levels, and routed to the appropriate team. High-confidence outputs are auto-routed, while uncertain cases are escalated for human review. All interactions are logged to enable performance monitoring and operational analytics.

The system is built using n8n for orchestration, OpenAI for classification and embeddings, Slack for routing, and Google Sheets for KPI tracking. The architecture reflects practical application of intelligent automation within operational workflows.

Mock Data and Results are used to show an example of how it would function in practice.
