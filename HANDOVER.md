# BiteBack App Handover

This document serves as a comprehensive handover for development in the Codex desktop app.

## Repository Structure
- `apps/`
  - `frontend/` - Mobile app (React Native) for BiteBack
  - `backend/` - Node.js + Python services
  - `ai_agents/` - RAG and autonomous task agents
  - `mini_game/` - 3D interactive mini-game
  - `assets/` - Mascot 2D/3D images, outfit sheets, UI mockups

## Mascot & Assets
- BiteBack Dog: Australian Cattle Dog mascot
- Outfits: Core Robe, Smart Business, Smart Casual Aussie, Outback Utility, Community Advocate, Tech Support, Coastal Ready, Formal Court
- Avatar images: 2D sprites & 3D models
- UI components & icons ready for integration

## Backend & AI
- RAG Knowledge Graphs: Australian laws, court cases, precedents, loopholes
- Autonomous Agents: Evidence collection, task automation, case prediction, continuous monitoring
- OpenAI integration: GPT-5-mini for AI guidance
- Security: End-to-end encryption, zero personal data access, compliance with Australian Privacy Principles

## Mini-Game
- 3D interactive mode for user engagement
- Mascot-guided tasks while automated processes run
- Game mechanics designed to keep users engaged while AI operates

## Development Notes
- GitHub repository: `joshohara-au/umitide`
- Branching strategy: `main` for stable releases, feature branches for modules
- CI/CD: Recommended for backend, frontend, and AI agent updates
- Documentation: Keep all architecture, security, and AI integration docs updated

## Next Steps
1. Populate `apps/assets` with mascot 2D/3D files
2. Implement React Native frontend in `apps/frontend/src`
3. Implement backend services in `apps/backend`
4. Configure AI agents and RAG pipelines in `apps/ai_agents`
5. Develop 3D mini-game scenes and scripts in `apps/mini_game`
6. Ensure security & compliance checks are in place for every module

This handover ensures a smooth continuation of BiteBack development using Codex desktop app, leveraging all prepared structures and assets.