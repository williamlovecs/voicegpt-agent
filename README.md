# VoiceGPT Agent (In Progress)

Project Description:
---------------------
A modular, real-time voice assistant built using Python, Whisper (Speech-to-Text), GPT-4 (language generation), and Edge TTS (Text-to-Speech). This project is designed to explore voice interface pipelines, agentic flow, and LLM-based interaction logic.

Core Features:
--------------
- Speech-to-Text: OpenAI Whisper
- Text Generation: OpenAI GPT-4 API
- Text-to-Speech: Microsoft Edge TTS
- Basic prompt chaining and turn-taking logic
- Modular Python architecture (CLI-based for now)
- Flask/Streamlit and Docker deployment planned

Tech Stack:
-----------
- Languages: Python 3.10+
- AI Components: Whisper, GPT-4 API, Edge TTS
- Backend (Planned): Flask / Streamlit
- Deployment (Planned): Docker + Google Cloud Platform
- Version Control: Git

```
Project Directory Plan:
------------------------
voicegpt-agent/
├── main.py
├── requirements.txt
├── modules/
│   ├── stt_whisper.py
│   ├── gpt_handler.py
│   └── tts_edge.py
├── prompts/
│   └── base_prompt.txt
├── demo/
│   └── sample_convo.mp3
├── README.txt
└── TODO.txt

```

Setup Instructions:
-------------------
1. Clone the repository:
   git clone https://github.com/your-username/voicegpt-agent.git

2. Navigate to project directory:
   cd voicegpt-agent

3. Install dependencies:
   pip install -r requirements.txt

4. Run the assistant:
   python main.py

TODO:
-----
- [ ] Implement Whisper STT module
- [ ] Connect GPT-4 API for prompt-based response
- [ ] Integrate Edge TTS for voice output
- [ ] Add Streamlit interface
- [ ] Dockerize the project
- [ ] GCP deployment setup

Author:
-------
Xin (William) Xu  
B.S. in Computer Science, The Ohio State University  
Bilingual: English & Mandarin  
LinkedIn: https://linkedin.com/in/xin-william-xu-4a5b2116a/

Note:
-----
This project is part of my transition into the Voice & Agentic AI space, aiming to gain hands-on experience in multimodal AI interfaces and LLM integration.
