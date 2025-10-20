# BestMode

**BestMode** is a custom mode for code agents (Claude, ChatGPT etc.) specifically optimized for desktop and mobile application development.

## About

BestMode is based on [Beast Mode 3.1](https://gist.github.com/burkeholland/88af0249c4b6aff3820bf37898c8bacf) but brings modifications better suited for software development needs rather than web development.


## Installation
Exactly as for Beast mode:
1. Go to the "agent" dropdown in VS Code chat sidebar and select "Configure Modes".
2. Select "Create new custom chat mode file"
3. Select "User Data Folder"
4. Give it a name (BestMode)
5. Paste in the content of bestmode.chatmode.md
6. Go back to the "agent" dropdown and select the new mode (BestMode)


## Usage

Simply start by describing your project:
- "Create a desktop application with Electron that..."
- "I want to develop a React Native mobile app for..."
- "Help me set up a Flutter project that..."

The agent will automatically follow BestMode's optimized workflows.

## Differences from Original Beast Mode

- Less emojis in chat and code/comments
- Less emphasis on internet research
- Less emphasis on tests all the time. Only do tests when the task is completed
- Fixes reference to `fetch_webpage` instead of `fetch` 
- More emphasis on thinking and producing correct code 
- No more automatic md file after each request unless specifically asked for, a concise summary is done in the chat
- Should document assumptions
- Adds considerations for performances
- Adds coding guidelines

