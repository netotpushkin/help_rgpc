# Connecting a Local Model

There are several ways to run a language model on a local device. Popular options include Ollama, LM Studio, KoboldCpp, and others. As an example, we’ll go through the setup using KoboldCpp.

## Connection Steps

1. Download an LLM in `.gguf` format. You can find suitable models, for example, on [Hugging Face](https://huggingface.co/).
2. Launch KoboldCpp:
	- Download and open the application.
	- In the launcher, specify the path to the downloaded model.
	- Enable the Remote Tunnel option and click Launch.

	![](../assets/image/llm-model/2.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/2.png#only-dark){.on-glb data-gallery="only-dark"}

3. After launching, a command-line window will appear. Look for the line: `Your remote OpenAI Compatible API...`. It will contain a temporary URL (for example: `https://john-loving-cm-lows.trycloudflare.com/v1`). Copy this URL.

	![](../assets/image/llm-model/3.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/3.png#only-dark){.on-glb data-gallery="only-dark"}

4. Add the host on the website:

	- Go to the Models catalog, open the Hosts tab, and click “Add Host”.
	- In the “Endpoint URL” field, paste the copied URL and append `/chat/completions` at the end (e.g., `https://john-loving-cmlows.trycloudflare.com/v1/chat/completions`).
	- Fill in the remaining settings as desired.

	![](../assets/image/llm-model/4.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/4_dark.png#only-dark){.on-glb data-gallery="only-dark"}

5. Create the model:
	- On the Models tab, click “Add Model”.
	- Specify:
		- Host — the host you created earlier;
		- Display Name — the name of the model for display;
		- Model Name — the exact name of the .gguf file;
		- Fill in the remaining parameters as desired.

	![](../assets/image/llm-model/5.png#only-light){.on-glb data-gallery="only-light"}
	![](../assets/image/llm-model/5_dark.png#only-dark){.on-glb data-gallery="only-dark"}

6. Click “Create Model” and wait a moment. After that, the model will appear in the list and be ready for use.