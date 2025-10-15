### Required environment variables for n8n workflows

- RELEVANCE_AUTH: Set to your Relevance API auth header value (format `projectId:secretKey`).
- SERPAPI_API_KEY: Your SerpAPI key.
- APIFY_API_TOKEN: Your Apify API token.

Set these in your n8n instance under Settings → Environment variables or in your deployment environment. The workflows reference them via `{{$env.VARIABLE_NAME}}`.


