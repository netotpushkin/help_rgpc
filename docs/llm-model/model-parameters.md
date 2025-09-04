# Model Parameters

These settings help control how the model generates the character's responses.

- Model — Select a suitable model for the character.
- Temperature — Controls the creativity of responses. Recommended value: 0.5–1.1. Higher values produce more diverse and unconventional answers.
- Top-P — Limits word selection to the most probable set covering probability P. For example, at P=0.9, the model selects words that collectively account for 90% of the probability.
- Top-K — Restricts word selection to the K most probable words. For example, at K=50, the model considers only the top 50 most likely words.
- Total Context Tokens — The maximum context size the model considers when generating a response.
- Max Response Tokens — Limits the length of the response. For English, approximately 100 tokens ≈ 70 words.
- Presence Penalty — Reduces the likelihood of repeating words already used. Higher values increase this effect.
- Frequency Penalty — Penalizes frequent repetition of the same words. Higher values reduce repetitiveness in expressions.

![](../assets/image/llm-model/1.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/llm-model/1_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! info

	For characters with a unique speaking style, you can increase the Temperature, while for precise and concise responses, it's better to decrease it.

	To reduce repetition, use Presence Penalty and Frequency Penalty at moderate values.