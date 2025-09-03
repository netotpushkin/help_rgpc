# Character Creation And Import

## Создание персонажа

Чтобы создать уникальный образ для общения и ролевых игр, нажмите «Create Character» на главной странице или в каталоге.

### Character Avatar

Аватар показывает, как выглядит ваш персонаж, и делает общение более живым. Вы можете:

- Загрузить картинку со своего устройства, нажав «Choose Image».
- Сгенерировать с помощью AI, нажав «Generate New Avatar».

![](assets/image/character/3.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/3_dark.png#only-dark){.on-glb data-gallery="only-dark"}

Для генерации введите описание в «Image Description», выберите модель в «Image Model», при необходимости активируйте NSFW (если нужны откровенные изображения), настройте Guidance Score для влияния описания на результат, и нажмите «Generate».

![](assets/image/character/4.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/4_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Basic Information

Укажите имя в поле «Name» (до 20 символов), выберите язык и добавьте краткое описание в «Description».

![](assets/image/character/5.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/5_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### First Messages

Выберите язык первого сообщения и добавьте варианты, нажав «Add Greeting». Можно создать до 10 приветствий. Отметьте «Default greeting for...», если хотите сделать его основным.

![](assets/image/character/6.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/6_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! info

	Первое сообщение — это приветствие, которое задаёт тон диалогу и влияет на поведение модели. Рекомендуем создать хотя бы одно приветствие на английском.

	Для выделения действий используйте `*звёздочки*`, а для реплик — `"кавычки"`.

	Используйте переменные `{{user}}` для обращения к игроку и `{{char}}` для обращения к персонажу.

### Backgrounds

Для каждого приветствия можно установить фон. Загрузите изображение («Choose file») или сгенерируйте («Generate New Backgrounds»). Максимум — 6 изображений. Чтобы привязать фон к приветствию, откройте меню «Assign to greeting» на нужной картинке и выберите сообщение.

![](assets/image/character/7.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/7_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Character Details

В «Personality Traits» опишите личность, черты, манеру речи и прошлое. В «Scenario» — ситуацию, в которой он находится. В «Example Dialogue» — пример разговора, отражающий стиль общения. В «Author's Note» — авторскую заметку, задающую тон повествования.

![](assets/image/character/8.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/8_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! info

	Используйте лаконичные формулировки, например: «бывший детектив», «говорит рифмами».

	Чтобы скрыть раздел от пользователей, снимите галочку «Visible to user».

### Choose a Prompt and AI Model

Выберите из рекомендаций промпт и AI-модель или нажмите «Select Custom» для выбора из списка.

![](assets/image/character/9.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/9_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Metadata

Укажите гендер, добавьте теги и настройте доступ:

- Private — только для вас;
- Unlisted — доступ по ссылке;
- Public — для всех.

![](assets/image/character/10.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/10_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Согласие с правила сообщества

Перед завершением установите галочку «I have read and agree to the Community Guidelines» и нажмите «Create Character».

![](assets/image/character/11.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/11_dark.png#only-dark){.on-glb data-gallery="only-dark"}

## Import Character

Вы можете загрузить готовый образ с устройства или импортировать его из интернета. Для этого откройте каталог персонажей и нажмите «Create Character».

Затем выберите способ импорта:

- Если файл на вашем устройстве, нажмите «Select File» и загрузите его. Поддерживаются форматы .json, .png и .jpg.
- Если у вас есть ссылка, вставьте её в поле «Character URL» и нажмите «Preview Character».

После импорта все поля заполнятся автоматически.

![](assets/image/character/12.png#only-light){.on-glb data-gallery="only-light"}
![](assets/image/character/12_dark.png#only-dark){.on-glb data-gallery="only-dark"}

!!! info

	Файл должен содержать всю необходимую информацию и соответствовать формату (лучше всего — спецификации V2 или V3).