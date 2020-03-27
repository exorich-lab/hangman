## Виселица (Hangman)

Игра [Виселица](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)) написанна на языке Ruby.

### Установка
Несколько простых шагов чтобы начать игру:

_Склонируйте репозиторий из GitHub_

```git clone git://github.com/exorich-lab/hangman.git```

_Перейдите в папку с игрой_

```cd hangman```

_Запустите игру_
```
ruby main.rb
```

### Правила игры
Слово для угадывания представлено рядом черточек, представляющих каждую букву слова.
<br> Собственные существительные, такие как имена, места и бренды, не допускаются.
Слова сленга, иногда называемые неформальными или сокращенными словами, также не допускаются.
<br> Если игрок предлагает букву, которая встречается в слове, программа записывает его во всех правильных положениях.
<br> Если предлагаемая буква не встречается в слове, программа рисует один элемент фигуры повешенного человека в виде метки.
<br> Если игрок угадал все буквы слова - игрок выигрывает
<br> Если игрок сделал 7 неудачных попыток - игра проиграна


### Добавляте свои слова
Отредактируйте words.txt в папке data
