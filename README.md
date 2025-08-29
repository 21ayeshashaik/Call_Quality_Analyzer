# Call Quality Analyzer

A Python-based tool to analyze sales call recordings with cutting-edge AI techniques. This project automatically calculates key call metrics like talk-time ratio, question count, longest monologue, call sentiment, and generates actionable insights from audio recordings.

## Features

- Automatic transcription using OpenAI Whisper ASR
- Advanced speaker diarization with pyannote.audio
- Calculation of talk-time ratios and longest monologues
- Intelligent question detection using NLP
- Multi-modal sentiment analysis (text + audio features)
- AI-generated actionable insights and summary
- Heuristic identification of sales rep vs customer
- Robust handling of poor audio quality
- Designed to run efficiently on free Google Colab tier

## Getting Started

### Prerequisites

- Python 3.8+
- ffmpeg installed (for audio processing)
- GPU recommended but not required

Install required packages:

