# Удалить все записи на стене Вконтакте

## Для того, чтобы использовать скрипт необходимо:
1. Открыть вашу страницу со стеной (лентой), нажав "Моя страница".
2. Прокрутить страницу до конца вниз. Можно мышью, можно стрелками, можно держать клавиши End или Page Down на клавиатуре на PC или fn+(стрелка вниз) на Mac OS.
3. Теперь для браузеров:

### Firefox
Инструменты -> Веб-разработка -> Веб-консоль
### Chrome
Нажимаем меню -> Инструменты -> Консоль Javascript

Вставляем наш скрипт:
```javascript
var i=0;
while (1==1)	{
	document.getElementsByClassName('post_delete_button')[i].onclick();
	i++;
}
```

Нажимаем Enter.

Если не домотали до конца вниз, можно обновить страницу и повторить последовательность.