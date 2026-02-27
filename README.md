# x-post-summarizer-2026

This project summarizes a public figure's 2026 X posts using AI.

## Account Analyzed

- Handle: @llm_wizard

## Project Overview

This project was built using a LangGraph agent with GitHub MCP tools for repository operations and the X API v2 for post retrieval.

## How to Replicate

1. Set up your X API Bearer Token:
   - Obtain your Bearer Token from the X Developer Portal.
   - Set it as an environment variable in your shell:
     ```bash
     export X_BEARER_TOKEN='your_bearer_token_here'
     ```

2. Install Python dependencies:
   ```bash
   pip install requests
   ```

3. Run the search script:
   ```bash
   python x_search.py [X_handle]
   ```
   Replace `[X_handle]` with the desired X account handle to analyze. Defaults to `llM_wizard` if not provided.

4. The script will save the retrieved posts to `posts.json`.

Feel free to explore and extend this project!
