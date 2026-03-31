# Gemini Text Response Generator

## Overview
This project reads structured prompts from prompts.py and generates
text responses using Google Gemini API. It automatically rotates to
the next API key when the current key's quota is exhausted.

## Project Structure
- main.py       → Core logic, API key rotation, response generation
- prompts.py    → All prompts with role and task structure
- config.py     → API keys and model configuration
- output.txt    → Generated responses (created after running)

## How to Run (Google Colab)
1. Upload Gemini_Text_Generator.ipynb to Google Colab
2. Run all cells in order (Cell 1 to Cell 6)
3. Output will be printed and saved to output.txt

## Features
- Multi-prompt processing (5 prompts)
- Automatic API key rotation on quota exhaustion
- Structured prompt format with Role and Task
- Output saved to output.txt

## Model Used
- gemini-2.0-flash

## API Keys
- Uses 2 API keys from 2 different Google accounts
- Auto-switches to Key 2 if Key 1 is exhausted
