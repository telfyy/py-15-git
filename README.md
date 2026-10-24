# Модуль mymod

***

_**Модуль з трьома функціями, які працюють зі списком текстових рядків, переданих як аргумент**_

***

### Функції та запуск:

> - **count_lines**(lines) — кількість рядків.
> - **count_chars**(lines) — загальна кількість символів.
> - **test**(lines) — викликає обидві функції та виводить результати у зручному для читання форматі.

***

#### Запуск скрипту:

```Bash
python my_file.py
```

#### Через імпорт:

```python
mymod.test(["hello Ukraine", "city: Lvyiv", "'car brand: Skoda", "USA, Florida"])
```

***

#### Чому git status не показав pycache?

`Тому що ми додали pycache в gitignore, тому Git її ігнорує.`

***

## AI log:

Обговорив з ментором призначення **_gitignore_**, розібрав причину відсутності **_pycache_** у відстеженні
та закріпив послідовність команд для фіксації змін у репозиторії.

## My history

```Branch
59912e7 (HEAD -> main, origin/main) Add AI log
be774f3 Add my README with info about project
7aeb209 Add my module and the script that uses it
b96286f Add .gitignore
```
