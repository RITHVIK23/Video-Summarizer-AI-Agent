# Phidata Video AI Summarizer 🎥🎤🖬

## Overview
Phidata Video AI Summarizer is a Streamlit-based application powered by Gemini 2.0 Flash Exp. This multimodal AI agent analyzes video content and provides actionable insights based on user queries. The app leverages cutting-edge AI models and web search tools for video summarization and context extraction.

## Features
- **Video Upload:** Supports file formats like `.mp4`, `.mov`, and `.avi`.
- **Custom Query:** Users can input specific questions or insights they want from the video.
- **AI-Powered Analysis:** Utilizes Gemini 2.0 Flash Exp for video content understanding and DuckDuckGo for supplementary research.
- **User-Friendly Interface:** Provides detailed, actionable responses in a clean and intuitive layout.

## Requirements
- Python 3.8 or later
- Streamlit
- phi-agent library
- Google Generative AI SDK
- DuckDuckGo API
- dotenv for environment variable management

## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/video-ai-summarizer.git
    cd video-ai-summarizer
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up the environment variable for the Google API key:
    - Create a `.env` file in the project root.
    - Add your API key:
      ```plaintext
      GOOGLE_API_KEY=your_api_key_here
      ```

4. Run the application:
    ```bash
    streamlit run app.py
    ```

## Usage
1. Upload a video file via the file uploader.
2. Enter a question or query in the text area about the video content.
3. Click the **Analyze Video** button to process and retrieve insights.
4. View the AI-generated analysis in the result section.

## File Structure
- `app.py`: Main application file.
- `requirements.txt`: List of Python dependencies.
- `.env`: Environment variables (not included; to be created by the user).

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Feel free to submit issues or pull requests to improve the app. Contributions are welcome!

## Acknowledgments
- [Streamlit](https://streamlit.io/)
- [Google Generative AI](https://developers.generativeai.google/)
- [DuckDuckGo](https://duckduckgo.com)

---
**Happy summarizing!**
