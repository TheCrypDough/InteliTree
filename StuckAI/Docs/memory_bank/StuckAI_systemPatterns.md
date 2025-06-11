# StuckAI - Key System Architectural Patterns & Design Insights
Last Updated: 2025-06-11 02:50:43

<!-- Droid to populate this with a detailed summary of chosen architectural patterns from Section 7 of the StuckAI_Creation_Guide_V2.0.md during its first Auto-Update Workflow. For now, a brief summary: -->

StuckAI employs a Hybrid Client Architecture (Electron for OS integration, IAT-WebApp Next.js for the Think Tank dashboard, IAT-Mobile React Native for the companion app). Backend logic is built as modular IAT-Microservices (Bun/Hono) on the InteliTree Base Stack. Event-Driven Architecture (NATS/Kafka) will manage real-time intelligence and context propagation. A Federated Knowledge Graph approach (Neo4j, Graphiti) will connect insights within StuckAI and across the wider InteliTree ecosystem. AI Agent Swarm Collaboration will use an Orchestrator-Worker pattern.
