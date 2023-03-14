**Нельзя менять index.html и index.css файлы** :warning: 

1) По клику на кнопку `Нажми на меня`, добавьте новую кнопку с `id="magic-btn-2"` и с текстом "Я изменю тебя" со стилями:  
   `background-color:  #a78b71;`  ( * в js будет backgroundСolor * )  
   `color: white;`  
2) Поменяйте стили кнопки `magic-btn` по клику на кнопку "Я изменю тебя" на:
   - цвет фона на `9c4a1a`;
   - цвет текста на черный;

    
*В файле index.js*: 
1) Кнопку получить можно через ```const btn = document.querySelector('#magic-btn')```
2) Добавить новую кнопку в body можно через `document.body.appendChild(elem);`
3) Поменять стили можно через объект style. Н-р: ```elem.style.color = "black"```
4) Для клика можно использовать ```btn.addEventListener('click', () => {})```.
5) Кнопка "Я изменю тебя" должна добавляться ТОЛЬКО после клика на кнопку "Нажми на меня!"
