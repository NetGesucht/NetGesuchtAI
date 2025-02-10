# NetGesucht AI Tools

This repository contains a collection of scripts, system prompts, and agent workflows designed to be used with the NetGesucht AI application.

## Directory Structure

- `scripts/`: Contains utility scripts including getNews functionality
- `system_prompts/`: Contains system prompt configurations
- `workflows/`: Contains agent workflow definitions

## Requirements

### Get News

To use the getNews functionality, you must obtain a valid API key from [NewsAPI](https://newsapi.org).

1. Register at [newsapi.org](https://newsapi.org/register)
2. Obtain your API key
3. Configure the key in the appropriate script, scripts/getNews.json

### Web Search

To use the web search functionality, you need a SerpAPI key:

1. Sign up at [serpapi.com](https://serpapi.com)
2. Obtain your API key
3. Configure the key in the appropriate script: scripts/webSearch.json, and workflow tool node: workflows/WebSearcher.json


## Usage

These tools are part of the NetGesucht AI ecosystem. The files here are used to configure and manage various AI behaviors and workflows.

Important: When importing components, always import scripts and system prompts BEFORE importing workflows to ensure proper initialization and dependencies.

## Contributing

Send Pull Requests (PRs) with your contributions.
