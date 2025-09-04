# System Prompt

This is a hidden instruction for the model that sets general rules of behavior in the dialogue. It does not replace the character's role but defines the overall style, constraints, and responses.

You can think of it this way: the system prompt is the director, while the character prompt is the actor.

## Creating a System Prompt

Go to the prompts catalog by clicking “Prompts” at the top of the page. Then click the “Create New Prompt” button and fill in the following fields:

![](assets/image/system-prompt/1.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/system-prompt/1_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Content

- Title — the name of the prompt;
- Description — briefly describe its purpose;
- Prompt Text — the actual text of the prompt: write clearly and without contradictions.

![](assets/image/system-prompt/2.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/system-prompt/2_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! info

	For general prompts, use universal rules. For specific ones, provide detailed instructions, for example, a writer's style or behavior in combat scenes.

	You can use template placeholders:
	- `{{user}}` — the user;
	- `{{char}}` — the character;
	- `<traits>`, `<scenario>`, `<greeting>`, `<example dialogue>` — character sections;
	- `<memories>` — chat memory.

!!! warning

	Do not make the prompt too long — it is sent with every request and quickly consumes the context.

### Metadata

- Visibility — access level:
	- Public — visible to everyone;
	- Private — only visible to you.
- Tags — add relevant keywords for search.

![](assets/image/system-prompt/3.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/system-prompt/3_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Model

- Click “Add Model Configuration” to add a recommended model. You can specify up to 10 models.
- To configure a model, click “Configure”.

![](assets/image/system-prompt/4.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/system-prompt/4_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! warning

	Make sure to add at least one model.

To save your prompt, click “Create Prompt”.