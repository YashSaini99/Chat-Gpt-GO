# CLI ChatGPT Application

A simple command-line interface (CLI) application that interacts with OpenAI's GPT-3 using Go. This tool allows you to have a conversation with GPT-3 directly from your terminal.

## Features

- **Interactive CLI:** Engage in a conversation with GPT-3 directly from the terminal.
- **Customizable:** Easily configure the API key via a `.env` file.

## Prerequisites

- Go 1.16 or later
- [OpenAI API Key](https://platform.openai.com/signup) (for accessing GPT-3)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/Chat-Gpt-GO.git
   cd Chat-Gpt-GO
   ```

2. **Install dependencies:**

   Make sure you have `go-gpt3` and `cobra` packages installed. Run:

   ```sh
   go mod tidy
   ```

3. **Create a `.env` file:**

   In the root of the project, create a `.env` file with the following content:

   ```env
   API_KEY=your_openai_api_key_here
   ```

## Usage

1. **Run the application:**

   ```sh
   go run main.go
   ```

2. **Interact with GPT-3:**

   - Type your message and press Enter.
   - Type `quit` to exit the application.

   Example:

   ```
   Say Something ('quit' to exit): Hello, how are you?
   ```
   
- **Dependencies**:
  - `github.com/PullRequestInc/go-gpt3`: Go client for OpenAI's GPT-3.
  - `github.com/spf13/cobra`: Command-line argument parsing.
  - `github.com/spf13/viper`: Configuration management.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/YashSaini99/Chat-Gpt-GO/blob/main/LICENSE) file for details.
