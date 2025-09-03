# Системный промпт

Это скрытая инструкция для модели, которая задаёт общие правила поведения в диалоге. Он не заменяет роль персонажа, а определяет общий стиль, ограничения и реакции.

Можно представить это так: системный промпт — режиссёр, а промпт персонажа — актёр.

## Создание системного промпта

Перейдите в каталог промптов, нажав «Prompts» в верхней части страницы. После нажмите на кнопку «Create New Prompt» и заполните следующие поля:

![Кнопка Create New Prompt](/assets/image/system-prompt/1.png#only-light)
![Кнопка Create New Prompt](/assets/image/system-prompt/1_dark.png#only-dark)

### Content

- Title — название промпта;
- Description — коротко опишите назначение;
- Prompt Text — сам текст промпта: пишите чётко, без противоречий.

![Вкладка Content](/assets/image/system-prompt/2.png#only-light)
![Вкладка Content](/assets/image/system-prompt/2_dark.png#only-dark)

!!! info

	Для общих промптов используйте универсальные правила. Для узких — конкретные, например, стиль писателя или поведение в боевых сценах.

	Можно использовать шаблонные ссылки:
	- `{{user}}` — пользователь;
	- `{{char}}` — персонаж;
	- `<traits>`, `<scenario>`, `<greeting>`, `<example dialogue>` — разделы персонажа;
	- `<memories>` — память чата.

!!! warning

	Не делайте промпт слишком длинным — он отправляется при каждом запросе и быстро расходует контекст.

### Metadata

- Visibility — доступ:
	- Public — для всех;
	- Private — только для вас.
- Tags — добавьте ключевые теги для поиска.

![Вкладка Metadata](/assets/image/system-prompt/3.png#only-light)
![Вкладка Metadata](/assets/image/system-prompt/3_dark.png#only-dark)

### Model

- Нажмите «Add Model Configuration», чтобы добавить рекомендуемую модель. Можно указать до 10 моделей.
- Для настройки модели нажмите «Configure».

![Вкладка Model](/assets/image/system-prompt/4.png#only-light)
![Вкладка Model](/assets/image/system-prompt/4_dark.png#only-dark)

!!! warning

	Обязательно добавьте минимум одну модель.

Чтобы сохранить ваш промпт нажмите «Create Prompt».