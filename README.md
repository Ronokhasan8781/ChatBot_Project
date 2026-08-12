<img width="1069" height="537" alt="Chatbot Project" src="https://github.com/user-attachments/assets/47da6aa2-2f6c-4fd0-942a-8e7a3ae8aacd" /># Project
✅ Create a voice-enabled support AI using LiveKit 
✅ Add a 3D AI avatar with Beyond Presence for a lifelike experience 
✅ Enable screen sharing so the agent can see your screen 
✅ Implement real actions — unblock users, send ticket emails, and more 
✅ Add typing sound effects (audio cues) and success notifications (visual cues)
### 🧠 System Architecture

```text
                    ┌─────────────────────┐
                    │        User         │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    │ Multimodal Input    │
                    │ Voice + Text +      │
                    │ Screen Context      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   AI Support Agent  │
                    │  Reasoning + Tools  │
                    └──────────┬──────────┘
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
       Voice Response      3D Avatar      Screen Analysis
             │                 │                 │
             └─────────────────┼─────────────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Real-World       │
                    │     Actions        │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        User Support      Ticket Email     Account Actions
