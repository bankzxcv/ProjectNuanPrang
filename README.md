# Weather Alert System as called "นวลปราง"

This Python script utilizes the LangChain library and various other libraries to create a system for analyzing weather websites, extracting relevant information about potential tornadoes, and alerting utility companies in the affected areas.

## Features

- Analyzes weather websites (e.g., https://www.nhc.noaa.gov/cyclones/) for potential tornado information
- Extracts relevant data such as tornado names, likelihood (1-5 scale), and estimated arrival times
- Searches for utility companies in the areas affected by potential tornadoes
- Alerts the identified utility companies about incoming weather events
- Utilizes language models like ChatAnthropic, Ollama, and OpenAI's ChatGPT-4
- Leverages tools for web crawling, searching, and information extraction
- Implements a multi-agent system using the CrewAI library
- Stores and retrieves weather-related information in a vector database (Chroma)

## Installation

1. Clone the repository:

```
git clone https://github.com/bankzxcv/tornado-alert-system.git
```

2. Install the required dependencies:

```
poetry install
```

3. Set up the environment variables:

```
cp .env.example .env
```

Edit the `.env` file and provide the necessary API keys for Anthropic, FirecrawlSearch, and OpenAI.

## Usage

1. Run the Jupyter notebook: ai_hack.ipynb

2. The script will analyze the weather website, extract relevant tornado information, search for utility companies in the affected areas, and provide a final output with the tornado details and a list of companies to be alerted.

3. The output will be printed line by line in the console.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain)
- [CrewAI](https://github.com/crewAIInc/crewAI)
- [FirecrawlSearch](https://github.com/mendableai/firecrawl)
- [DuckDuckGoSearch](https://python.langchain.com/v0.2/docs/integrations/tools/ddg/)
- [Anthropic](https://www.anthropic.com/)
- [Ollama](https://ollama.com/)
- [OpenAI](https://openai.com/)