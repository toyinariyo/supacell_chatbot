# Supacell Character Chatbot

## Overview

This project is an interactive chatbot that lets users talk to the 5 main characters from the Netflix series [Supacell](https://en.wikipedia.org/wiki/Supacell).

## Features
- **Curated Q&A:** The chatbot uses a set of pre-written questions and answers to ensure responses are accurate and true to each character.
- **Character Authenticity:** Each character's responses reflect their personality, speech patterns, and relationships from the show.
- **Prompt Engineering:** The system combines pre-written answers with AI-generated text.

## Technologies that were used for this project

- Python 3.11
- Hugging Face Transformers (for optional generative responses)
- Gradio (for the web interface)
- NLTK (for text processing)

## How the chatbot works

1. Loads detailed character profiles and Q&A from `character_profiles.txt`.
2. Matches user questions to prewritten answers for reliability.
3. Applies character-specific speech patterns for realism.
4. Optionally uses a language model for open-ended questions.

## Example Conversation
>**User:** How did you discover your ability?
>**Sabrina:** I discovered it in the worst possible way. I found out Kevin was cheating on me. I was so angry, and suddenly he was thrown against the door without me touching him.

## Demo

![User asks Tazer a question](supacell_chatbot_tazer_power_question.jpeg)
![Tazer answers the question](supacell_chatbot_tazer_power_answer.jpeg)
