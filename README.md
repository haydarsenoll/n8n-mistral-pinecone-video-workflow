AI Agent for Automating Video Idea & Script Generation

This repository contains a personal AI Agent workflow designed to automate AI-powered video content planning, idea generation, and script drafting using:

n8n for workflow orchestration

Mistral API for prompt-based text generation

Pinecone for vector storage and semantic memory

Simple Memory & Vector Store for conversation context management

🚀 Features

✅ AI-powered video idea generation✅ Automated title & hashtag suggestions✅ Shorts script generation✅ Context-aware personalized recommendations✅ Semantic search and long-term memory with Pinecone✅ Prompt engineering for flexible content outputs✅ Multi-turn conversation support✅ Easily extensible and versionable workflow

📸 Screenshots



🛠️ How to Use

1️⃣ Clone this repository:

git clone https://github.com/yourusername/ai-video-agent-n8n-mistral-pinecone.git

2️⃣ Import n8nagent.json into your n8n instance.

3️⃣ Set your environment variables:

MISTRAL_API_KEY

PINECONE_API_KEY

PINECONE_ENVIRONMENT

PINECONE_INDEX

4️⃣ Trigger via When Chat Message Received node to start your personal AI agent.

⚡ Prompts

Check the prompts/ folder for ready-to-use prompt examples:

Title & hashtag generation

Video script drafting

🧩 Requirements

n8n

Mistral API access

Pinecone account

Basic familiarity with workflow orchestration

🤝 Contribution

Feel free to fork, modify, and suggest improvements via PR.

📄 License

MIT

📂 Recommended Folder Structure

/ (root)
│
├── README.md
├── workflow/
│    ├── ai_video_agent_n8n_workflow.json
│    └── screenshots/
│         └── workflow_overview.png
│
├── prompts/
│    ├── shorts_title_generation.md
│    ├── script_generation_prompt.md
│
└── requirements.md

Bu yapıyı olduğu gibi GitHub’a yükleyebilir, LinkedIn postuna veya proje portföyüne ekleyebilirsin.
