---
title: Проброс событий DOM
---

Проброс событий работает и для событий DOM.

Мы хотим получать уведомления о кликах по нашей красивой кнопке `<FancyButton>` — для этого нам просто нужно пробросить событие `click` по элементу `<button>` в `FancyButton.svelte`:

```html
<button on:click>
	Нажми меня
</button>
```