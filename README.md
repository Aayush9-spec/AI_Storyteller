🎭 AI Storyteller

An AI-powered interactive storytelling tool that generates stories, narrates them with speech, and allows customization for creativity and fun.

🚀 Features

📖 AI Story Generation using NLP (transformers)

🗣️ Text-to-Speech (TTS) with gTTS

🎨 Customizable Stories (characters, themes, genres)

🎧 Audio Story Output – listen instead of reading

📦 Easy deployment on Google Colab or locally

🛠️ Installation

Clone the repo:

git clone https://github.com/your-username/AI_Storyteller.git
cd AI_Storyteller


Install dependencies:

pip install -r requirements.txt


Or manually:

pip install transformers torch gtts reportlab Pillow

▶️ Usage
Run locally
python ai_storyteller_.py

Run on Google Colab

Open the .ipynb file in Google Colab

Run all cells

Enter prompts for story generation

📂 Project Structure
AI_Storyteller/
│── ai_storyteller_.py       # Main script
│── AI_Storyteller.ipynb     # Colab Notebook
│── requirements.txt         # Dependencies
│── README.md                # Project documentation

📸 Example

Input:
"Tell me a fantasy story about a dragon and a young wizard."

Output:
A narrated story with AI-generated text + speech.

🤝 Contributing

Pull requests are welcome! If you’d like to add new features (like more voices, story styles, or UI improvements), feel free to fork and submit a PR.

📜 License

This project is licensed under the MIT License.
