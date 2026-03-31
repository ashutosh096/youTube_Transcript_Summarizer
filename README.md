🎬 TranscriptAI — YouTube Transcript Summarizer
TranscriptAI is a sleek, modern web application that allows you to summarize any YouTube video in seconds. By extracting the transcript and processing it through Claude AI, it provides intelligent summaries without requiring you to watch the video.

⚡ Features
Instant Summaries: Get results in under 10 seconds for most videos.

3 Summary Styles: Choose between Brief (concise), Detailed (structured), and Bullet Points.

Smart Metadata: Displays video title, channel name, word count, and estimated reading time.

Export Options: Easily Copy the summary to your clipboard or Download it as a .txt file.

Fallback Logic: If no Anthropic API key is provided, the app uses an extractive summarization algorithm to pick key sentences automatically.

🛠️ Tech Stack
Frontend: HTML5, CSS3 (Modern Glassmorphism UI), JavaScript (Vanilla).

Backend: FastAPI (Python).

AI Engine: Claude AI (claude-sonnet-4-20250514).

Data Sourcing: youtube-transcript-api and YouTube oEmbed.

🚀 Quick Start
Clone the repository and install dependencies:

Bash
pip install -r requirements.txt
Set your Anthropic API Key (Recommended):

Windows: set ANTHROPIC_API_KEY=your_key_here

Mac/Linux: export ANTHROPIC_API_KEY=your_key_here

Launch the server:

Bash
uvicorn main:app --reload --port 8000
Open in your browser:
Navigate to http://localhost:8000.
![image alt](https://github.com/ashutosh096/youTube_Transcript_Summarizer/blob/82cbc5bd2fd9e36b8be5ff155072240fe73b4015/Screenshot%202026-03-31%20225831.png)
![image alt](https://github.com/ashutosh096/youTube_Transcript_Summarizer/blob/34d6f1da0a22060cec8857bc135910af68811220/Screenshot%202026-03-31%20225840.png)
