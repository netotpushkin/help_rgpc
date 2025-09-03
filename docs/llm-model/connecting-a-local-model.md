# Connecting A Local Model

Есть несколько способов развернуть языковую модель на локальном устройстве. Среди популярных решений — Ollama, LM Studio, KoboldCpp и другие. В качестве примера разберём установку через KoboldCpp.

## Шаги подключения

1. Загрузите LLM в формате `.gguf`. Найти подходящую модель можно, например, на [Hugging Face](https://huggingface.co/).
2. Запустите KoboldCpp
	- Скачайте и откройте приложение.
	- В лаунчере укажите путь к скачанной модели.
	- Отметьте опцию Remote Tunnel и нажмите Launch.

	![](assets/image/llm-model/2.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/2.png#only-dark){.on-glb data-gallery="only-dark"}

3. После запуска появится окно с командной строкой. Найдите строку: `Your remote OpenAI Compatible API...`. В ней будет временная ссылка (например: `https://john-loving-cm-lows.trycloudflare.com/v1`). Скопируйте её.

	![](assets/image/llm-model/3.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/3.png#only-dark){.on-glb data-gallery="only-dark"}

4. Добавьте хост на сайте
	- Перейдите в каталог моделей, вкладка «Hosts», нажмите «Add Host».
	- В поле «Endpoint URL» вставьте скопированную ссылку и добавьте в конец `/chat/completions` (пример: `https://john-loving-cmlows.trycloudflare.com/v1/chat/completions`)
	- Остальные настройки заполните по желанию.

	![](assets/image/llm-model/4.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/4_dark.png#only-dark){.on-glb data-gallery="only-dark"}

5. Создайте модель
	- На вкладке «Models» нажмите «Add Model».
	- Укажите:
		- Host — ранее созданный хост;
		- Display Name — название модели для отображения;
		- Model Name — точное имя `.gguf`-файла;
		- Остальные параметры заполните на свое усмотрение.

	![](assets/image/llm-model/5.png#only-light){.on-glb data-gallery="only-light"}
	![](assets/image/llm-model/5_dark.png#only-dark){.on-glb data-gallery="only-dark"}

6. Нажмите «Create Model» и немного подождите. После этого модель появится в списке и будет готова к использованию.