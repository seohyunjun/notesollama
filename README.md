<img width="128" src="notesollama-icon.png" />

# NotesOllama

Use [Ollama](https://ollama.com) to talk to local LLMs in Apple Notes. Inspired by [Obsidian Ollama](https://github.com/hinterdupfinger/obsidian-ollama). Why should Obsidian have all the nice plugins?

## Demo

<video width="800" src="https://github.com/andersrex/notesollama/assets/1891619/d289d5b3-1e30-4aa3-a34a-fd2a6fa888d0"></video>

## Stack

- SwiftUI for user interface
- [AXSwift](https://github.com/tmandry/AXSwift) to access Notes through macOS's accessibility API
- [OllamaKit](https://github.com/kevinhermawan/OllamaKit) to interface with Ollama

## Usage

Open the project in Xcode to run, or download the binary [here](https://smallest.app/notesollama).

NotesOllama assumes your have Ollama running on the default macOS port (http://localhost:11434).

You can change the default prompts by editing the commands.json file:

`$ vim NotesOllama.app/Contents/Resources/commands.json`

## License

MIT License

Copyright (c) 2024 Anders Rex
