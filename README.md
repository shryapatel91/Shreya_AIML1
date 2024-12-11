
# smartSense Assessment (for AI/ML Engineer I role)
github link: https://github.com/shryapatel91/Shreya_AIML1.git

## Goal: 
This project addresses the inefficiencies that often arise in meetings, such as off-topic discussions, low
engagement, and unproductive outcomes. With the AI-powered meeting Assistant Bot, we aim to
automate meeting transcriptions, analyze productivity, and evaluate participant engagement.


**Note:** This repo contains the implementation of audio processing and transcription

## Instructions:

- Install required libraries through the command:
```bash
    pip install librosa openai-whisper ffmpeg-python
```
- Run the given notebook


## Possible Strategy:
**1. Transcription:**

- Challenges: Background noise, accents, and varying speech speeds.
- Solution: Use a reliable speech-to-text tool (e.g., Google Speech-to-Text, Whisper by OpenAI).
- Preprocessing: Noise reduction, silence trimming.

**2. Analysis:**

- Productivity Analysis: Identify keywords related to decision-making (e.g., "approve", "finalize") using rule-based approaches or text classification models.
- Time Wastage Detection: Analyze repetitive phrases or excessive pauses using TF-IDF or similarity checks.
- Participant Engagement: Measure speaking time, interruptions, and identify dominant speakers.
- Flow Analysis: Detect topic changes using NLP techniques like embeddings or topic modeling.

**3. Tone Detection:**
- Fine-tune a pre-trained model (e.g., BERT) or train a CNN/LSTM model for sentiment analysis.
**4. Flow Detection:**
- Use sequence modeling (e.g., RNNs or Transformers) to analyze conversation patterns.

**5.Insights and Recommendations:**

- Summarize analyses to generate actionable advice. Example: "Participant X dominated 80% of the meeting. Encourage balanced participation."

**6.Automation:**

- Leverage APIs or libraries (e.g., Google Calendar API) for task scheduling and email generation.
