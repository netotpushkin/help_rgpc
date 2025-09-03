# Lore Book

Это набор заметок, которые помогают модели лучше понимать контекст диалога. Когда в вашем сообщении встречаются определённые слова или создаётся нужная ситуация, система автоматически добавляет подходящую запись в контекст, чтобы ответы были точными и осмысленными.

## Добавление новой записи в книгу

Перейдите на страницу персонажа и под аватаром нажмите «Lore». Затем:

- Нажмите «Add Entry».
- В поле «Title» введите название записи.
- В блоке «Trigger Configuration» выберите тип срабатывания:
	- Keywords — запись активируется при появлении указанных слов;
	- Semantic — запись добавляется по смыслу, если AI определит подходящий контекст.

![](../assets/image/character/15.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/15_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Keywords

- Case Sensitive — учитывает регистр букв.
- Match All Keywords — срабатывает только при обнаружении всех слов.
- В «Keywords» укажите ключевые слова через запятую.
- В разделе «Action Configuration» выберите, что произойдёт при срабатывании:
	- Add to Context — добавить запись в память диалога;
	- Send Message — отправить сообщение в чат;
	- Send Image — отправить изображение (можно добавить текст);
	- Update Chat Avatar — заменить аватар персонажа.

![](../assets/image/character/16.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/16_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Semantic

- В «Context Description» опишите, когда должна срабатывать запись (например: «обсуждение магии», «разговор о прошлом персонажа»).
- В «Additional Instructions for AI» (необязательно) укажите реакцию AI, например эмоции.
- В «Action Configuration» выберите действие:
	- Send Message — отправить текст;
	- Send Image — картинку с текстом (опционально);
	- Update Chat Avatar — заменить аватар.

![](../assets/image/character/17.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/17_dark.png#only-dark){.on-glb data-gallery="only-dark"}

## Описание действий

- Add to Context — введите информацию в поле «Would be added to context», она будет учитываться в ответах персонажа.
- Send Message — добавьте текст в «Would be sent to chat from character side», и он отправится в чат.
- Send Image — загрузите изображение («Choose File») и, при желании, добавьте сопроводительный текст.
- Update Chat Avatar — загрузите новое изображение для аватара. Можно добавить текст, который появится вместе с заменой.

## Приоритет и вероятность

- Priority — чем выше, тем раньше сработает триггер при совпадении нескольких условий.
- Probability — задаёт вероятность срабатывания (чем выше, тем чаще).

![](../assets/image/character/18.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/18_dark.png#only-dark){.on-glb data-gallery="only-dark"}

Чтобы сохранить запись, нажмите «Create».