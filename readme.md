# Simple Bash AI

Simple bash AI assistant using OpenAI GPT. Ask for any bash script functionality.

This simple script aims to give bash script responses to queries.

This script does not execute any bash script from OpenAI Responses, it just returns answers to your terminal window.

## Installation

```bash
gh repo clone mihaliak/bash-ai
mv bash-ai/ai.sh /usr/bin/ai
chmod +x /usr/bin/ai
```

This script requires your OpenAI API Key in `OPENAI_KEY` env variable, you can set it using:

```bash
echo "\nOPENAI_KEY=\"YOUR_API_KEY_HERE\"" >> ~/.bash_profile
```

After that restart your terminal window or open new window.

## Usage

```bash
ai "list yaml files in current directory"
```