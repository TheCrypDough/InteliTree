# StuckAI - Core Technology Stack Context
Last Updated: 2025-06-11 02:50:54

<!-- Droid to populate this with a detailed summary of the chosen tech stack from Section 6 of the StuckAI_Creation_Guide_V2.0.md during its first Auto-Update Workflow. For now, a brief summary: -->

StuckAI is built on the InteliTree Base Stack (IBS), leveraging K3s, Supabase (Postgres, Auth, Vector), Neo4j, and the InteliTree AI Engine (IAIE) featuring LiteLLM for multi-model AI access. 
Client applications include:
*   **Desktop:** Electron (Node.js).
*   **Dashboard (Think Tank):** IAT-WebApp (Next.js, TypeScript, Shadcn/UI, Tailwind CSS, React Flow/Vis Network).
*   **Mobile:** IAT-Mobile (React Native, Expo, Tamagui).
Backend services are IAT-Microservices (Bun, Hono, TypeScript, Drizzle ORM).
Key technologies for advanced features include Tesseract.js (OCR), platform-specific Accessibility APIs, NATS/Kafka (event bus), RobotJS/Puppeteer (UI automation), and AR SDKs (e.g., VisionOS).
