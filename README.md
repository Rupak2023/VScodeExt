# Fix by AI - VSCode Extension

A powerful VSCode extension that allows you to fix code errors using multiple AI providers (Google Gemini and OpenAI) through inline quick fixes, similar to GitHub's code suggestions. Supports all programming languages with optimized prompts for C# and TypeScript.

## Features

- **Multi-AI Support**: Choose between Google Gemini and OpenAI GPT models.
- **Universal Language Support**: Works with any programming language detected by VSCode.
- **Optimized for C# and TypeScript**: Special prompts for better error fixing in these languages.
- **Inline Quick Fixes**: Hover over error squiggles and see light green popup with AI fix options.
- **Secure API Handling**: Store your API keys securely in VSCode settings.

## Installation

### From VSCode Marketplace (Recommended)

1. Open VSCode.
2. Go to Extensions (Ctrl+Shift+X).
3. Search for "Fix by AI".
4. Click Install.

### Manual Installation

1. Download the `.vsix` file from the [Releases](https://github.com/Rupak2023/fix-by-ai-extension/releases) page.
2. In VSCode, go to Extensions > ... > Install from VSIX.
3. Select the downloaded `.vsix` file.

## Setup

1. After installation, open VSCode settings (Ctrl+,).
2. Search for "Fix by AI".
3. Configure your settings:
   - **Provider**: Select "gemini" or "openai".
   - **Gemini API Key**: Your Google Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
   - **OpenAI API Key**: Your OpenAI API key from [OpenAI Platform](https://platform.openai.com/api-keys).


## Usage

1. Open any code file in VSCode with errors (red squiggles).
2. Hover your mouse over the error squiggle.
3. A light green popup will appear with quick fix options.
4. Click on "Fix with Gemini" or "Fix with OpenAI".
5. A progress bar will show the AI processing status.
6. A modal dialog will display the original code and the AI-generated fix.
7. Choose "Accept Fix" to apply the changes or "Decline Fix" to cancel.
8. The code will be replaced inline with the accepted fix.

## Supported Languages

- All languages supported by VSCode syntax highlighting.
- Special optimizations for:
  - C# (csharp, cs)
  - TypeScript (typescript, ts)

## Requirements

- VSCode 1.74.0 or higher.
- Valid API key for your chosen AI provider.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the ISC License.

## Publisher

Published by Rupak2023 - [GitHub](https://github.com/Rupak2023)

## Repository

[https://github.com/Rupak2023/fix-by-ai-extension](https://github.com/Rupak2023/fix-by-ai-extension)
