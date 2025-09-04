# Connecting the Model via OpenRouter

OpenRouter is a platform that allows you to connect to various AI models for text generation and other tasks.

## Connection Steps:

1. Create an API key:
	- Go to [OpenRouter](https://openrouter.ai).
	- Sign up and generate an API key.
2. Add the host:
	- On our website, go to Models → Hosts → Add Host.
	- In the Endpoint URL field, enter: `https://openrouter.ai/api/v1/chat/completions`
	- Paste your API key into the Access Token field.
	- Click “Create Host”.

	![](../assets/image/llm-model/6.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/6_dark.png#only-dark){.on-glb data-gallery="only-dark"}

3. Add a model:

	- Go to the Models tab and click Add Model.
	- Fill in the fields:
		- Host — select a previously created host.
		- Display Name — the display name for the model.
		- Model Name — the exact model name from the OpenRouter website (e.g., `mistralai/mistral-7b-instruct`).
		- Fill in the remaining parameters as needed.

	![](../assets/image/llm-model/5.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/5_dark.png#only-dark){.on-glb data-gallery="only-dark"}

5. Save the model:
	- Click Create Model and wait until the model appears in the list.