# Connecting The Model Via OpenRouter

OpenRouter — это платформа, которая позволяет подключаться к разным ИИ-моделям для генерации текста и других задач.

## Шаги подключения:

1. Создайте API-ключ:
	- Перейдите на [OpenRouter](https://openrouter.ai).
	- Зарегистрируйтесь и сгенерируйте API Key.
2. Добавьте хост:
	- На нашем сайте откройте вкладку «Models» → «Hosts» → «Add Host».
	- В поле Endpoint URL введите: `https://openrouter.ai/api/v1/chat/completions`
	- Вставьте ваш API Key в поле «Access Token».
	- Нажмите «Create Host».

	![](assets/image/llm-model/6.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/6_dark.png#only-dark){.on-glb data-gallery="only-dark"}

3. Добавьте модель:
	- Перейдите во вкладку «Models» и нажмите «Add Model».
	- Заполните поля:
		- Host — выберите ранее созданный хост.
		- Display Name — название модели для отображения.
		- Model Name — точное имя модели с сайта OpenRouter (например: `mistralai/mistral-7b-instruct`).
		- Остальные параметры заполните на свое усмотрение.

	![](assets/image/llm-model/5.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/5_dark.png#only-dark){.on-glb data-gallery="only-dark"}

5. Сохраните модель:
	- Нажмите «Create Model» и дождитесь, пока модель появится в списке.