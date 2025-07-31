# Market Simulation Deck
An AI-powered laboratory for uncovering latent market needs through simulated, data-driven conversations.
(Nota: Sostituisci questo link con uno screenshot reale della tua applicazione in funzione)

# 🚀 Core Philosophy
Traditional market research is flawed. Surveys, interviews, and focus groups often produce filtered answers because people tell you what they think you want to hear.
Market Simulation Deck flips the script.
Instead of asking questions, it allows you to listen to authentic, emergent dialogue. By simulating realistic conversations between data-driven customer personas, you can observe their unfiltered needs, desires, and pain points as they arise naturally. Your role is not to be a participant, but a strategic Observer.

# ✨ Key Features
Data-Driven Persona Synthesis: Leverages a (simulated) Qloo API to transform demographic and location data into high-fidelity customer profiles with realistic tastes, brand affinities, and frustrations.
Autonomous Dialogue Simulation: Deploys AI agents powered by Large Language Models (like Google Gemini or OpenAI's GPT) to engage in natural, unscripted conversations based on their core personalities.
AI-Powered Strategic Analysis: After the simulation, a dedicated AI Analyst processes the entire conversation to deliver a structured, actionable intelligence report.
Interactive Guided Demo Mode: A fully scripted, self-explanatory tour that showcases the application's full potential without requiring any API keys.
Mission Export/Import: Save and load your complete mission configurations (personas, scenarios, etc.) as JSON files for repeatable experiments.
Zero-Setup, Single-File Application: The entire tool is contained within a single HTML file. No installation, no dependencies, no build steps required. Just open it in a browser.

# 🚀 How to Use
Getting started is incredibly simple.
1. Download & Run
Download the market-simulation-deck-vX.X.html file from this repository.
Open the file in a modern web browser (like Chrome, Firefox, or Edge). That's it!
2. Running the Guided Demo (Recommended First Step)
The application starts in Demo Mode by default. This is a fully choreographed showcase that requires no API keys and is the best way to understand the tool's workflow.
Upon opening the file, a Guided Tour will begin automatically.
A message box at the top of the screen will provide step-by-step instructions.
The tour will guide you to:
Open the Mission Configuration panel.
Observe as it explains the Setup, Personas, and Scenario tabs.
Click to generate the pre-scripted, data-driven personas.
Deploy the simulation to watch the conversation unfold.
At the end of the simulated dialogue, an AI Analyst will automatically generate the final strategic report.
3. Using the "Live Mode"
To run your own custom simulations with live data, you need to switch to Live Mode.
Disable Demo Mode: In the "Configure Mission" panel, click the "Demo Mode Active" toggle to switch it off.
Enter API Keys: In the 1. Setup tab, enter your own API keys:
Qloo API Key: Required for generating new, data-driven personas based on real-world cultural data.
Google Gemini API Key: Required for powering the persona conversations and the final analysis.
OpenAI API Key (Optional): Can be used as an alternative LLM for the personas.
Configure Your Mission: Follow the standard workflow:
Go to the 2. Personas tab, define your target location and age group, and click "Generate Profiles".
Go to the 3. Scenario tab and write the discussion topic.
Deploy: Close the panel and click "Deploy Simulation".
methodology The Strategic Workflow
Whether in Demo or Live mode, the methodology remains the same. Follow these five phases for the best results:
Phase 1: SETUP
Define the technical parameters of your mission (API Keys) and manage your saved mission data (Import/Export).
Phase 2: PERSONAS
This is the core input. You provide the high-level demographic data (e.g., "Brooklyn, 22-25"), and the system synthesizes the detailed, realistic customer profiles.
Phase 3: SCENARIO
You define the "why." Frame an open-ended topic that encourages the personas to discuss their problems, needs, and desires.
Phase 4: OBSERVE
Deploy the simulation and watch the conversation unfold. Your role is to listen for recurring themes, emotional language, and specific pain points.
Phase 5: DEBRIEF
Review the AI-generated intelligence report. Use the interactive sections to drill down into latent needs and use the "Generate Business Canvas" feature to instantly start brainstorming strategic solutions.

# 🛠️ Technical Details
Stack: Vanilla HTML, CSS, and JavaScript.
Dependencies: None.
Architecture: The entire application is encapsulated within a single app object in the script to manage state and logic without a formal framework.

# 🗺️ What's Next (Roadmap)
This single-file application is a powerful proof-of-concept. The next logical steps for development include:
Migrating to a Modern Framework: Rebuilding the application in React/Svelte to better manage complexity and add more advanced features.
Developing a Simple Backend: Creating a Node.js/Express backend to securely manage API keys server-side and to save/load missions to a database.
Advanced Simulation Features:
Allowing a dynamic number of agents (3+ personas).
Introducing a "Message Inject" feature to test hypotheses mid-simulation.
Enhanced Analytics: Expanding the final debrief into a more advanced, interactive visual dashboard with sentiment analysis and keyword tracking.

# 📜 License
This project is licensed under the MIT License.
