# Im-mrmeeseeks-look-at-me
📌 Project Meeseeks – AI Task Agent System

Project Meeseeks is a local, AI-powered multi-agent system inspired by Mr. Meeseeks. Agents are spawned to complete specific tasks, age visibly in the UI, experience stress, and can spawn sub-agents to help them before disappearing upon task completion.

## 🖥️ Tech Stack
* **Frontend:** Godot Engine (UI, Agent visual states, Animations)
* **Backend:** Python (WebSocket server, Agent Manager)
* **LLM Provider:** Local Ollama (e.g., Llama 3, Phi-3)
* **Communication:** WebSockets (Real-time bridging between Godot and Python)
* **Memory:** JSON-based short-term memory

## 🚀 Setup Instructions (WIP)
1. Clone the repository.
2. Install [Ollama](https://ollama.com/) and pull your preferred local model.
3. Navigate to the `/backend` folder and run `pip install -r requirements.txt`.
4. Start the Python server: `python main.py`.
5. Open the `/frontend` folder in Godot and press Play!
