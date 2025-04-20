# Snowflake Audio Interfaces

This project implements speech-to-text and text-to-speech capabilities in Snowflake using Snowpark Container Services.

## Features
- 🎙️ Speech-to-Text with Whisper models
- 🔊 Text-to-Speech with Facebook's MMS models
- 💬 Conversational interface with Snowflake-hosted LLMs
- 🚀 GPU-accelerated inference

## Setup
1. Run `setup.sql` in Snowflake (as ACCOUNTADMIN)
2. Execute the notebooks to deploy services
3. Launch the Streamlit app

## Requirements
- Snowflake account with ACCOUNTADMIN privileges
- GPU-enabled compute pool (recommended)
