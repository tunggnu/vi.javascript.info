
Делаем цикл, пока посетитель что-то вводит -- добавляет `<li>`.

Содержимое в `<li>` присваиваем через `document.createTextNode`, чтобы правильно работали &lt;, &gt; и т.д.