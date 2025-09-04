# Lore Book

This is a set of notes that helps the model better understand the dialogue context. When certain words appear in your message or a specific situation arises, the system automatically adds the relevant entry to the context, ensuring accurate and meaningful responses.

## Adding a New Entry to the Lore Book

Go to the character’s page and click “Lore” under the avatar. Then:

- Click “Add Entry”.
- In the “Title” field, enter the entry’s name.
- In the “Trigger Configuration” section, choose the trigger type:
	- Keywords — the entry is activated when the specified words appear;
	- Semantic — the entry is added based on meaning if the AI detects a relevant context.

![](../assets/image/character/15.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/15_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Keywords

- Case Sensitive — considers letter case.
- Match All Keywords — triggers only when all specified words are found.
- In “Keywords”, list the keywords separated by commas.
- In the “Action Configuration” section, choose what happens when triggered:
	- Add to Context — add the entry to the chat memory;
	- Send Message — send a message in the chat;
	- Send Image — send an image (you can include text);
	- Update Chat Avatar — change the character’s avatar.

![](../assets/image/character/16.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/16_dark.png#only-dark){.on-glb data-gallery="only-dark"}

### Semantic

- In “Context Description”, describe when the entry should trigger (e.g., “discussion about magic,” “talking about the character’s past”).
- In “Additional Instructions for AI” (optional), specify the AI’s reaction, such as emotions.
- In “Action Configuration”, choose the action:
	- Send Message — send text;
	- Send Image — send an image with optional text;
	- Update Chat Avatar — change the avatar.

![](../assets/image/character/17.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/17_dark.png#only-dark){.on-glb data-gallery="only-dark"}

## Action Descriptions

- Add to Context — enter information in the “Would be added to context” field; it will be considered in the character’s responses.
- Send Message — add text in “Would be sent to chat from character side”, and it will be sent in the chat.
- Send Image — upload an image (“Choose File”) and optionally add accompanying text.
- Update Chat Avatar — upload a new avatar image. You can also add text that appears with the change.

## Priority and Probability

- Priority — the higher the value, the sooner the trigger will activate when multiple conditions match.
- Probability — sets the chance of triggering (the higher, the more often it occurs).

![](../assets/image/character/18.png#only-light){.on-glb data-gallery="only-light"}
![](../assets/image/character/18_dark.png#only-dark){.on-glb data-gallery="only-dark"}

To save the entry, click “Create”.