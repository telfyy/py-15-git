# Модуль mymod

***

_**Модуль з трьома функціями, які працюють зі списком текстових рядків, переданих як аргумент**_

***

### Функції:

> - **count_lines**(lines) — кількість рядків.
> - **count_chars**(lines) — загальна кількість символів.
> - **test**(lines) — викликає обидві функції та виводить результати у зручному для читання форматі.

***

## Як запустити

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

Тому що ми додали pycache в gitignore, через що Git ігнорує pycache.

---

## AI log:

- Обговорив з ментором призначення **_gitignore_**,
- розібрав причину відсутності **_pycache_** у відстеженні
- закріпив послідовність команд для фіксації змін у репозиторії,
- розібрав розшифровку помилок Git, закріпив різницю між збереженням файлу на диску та додаванням до staging area (зони
  підготовки),
- завершив оформлення README.

## My history

```Branch
cb80777 (HEAD -> main, origin/main, origin/HEAD) Merge pull request #1 from telfyy/improve-readme
13f4d64 (origin/improve-readme, improve-readme) Update README and add doc for functions in mymod
80b7a70 Update README
59912e7 Add AI log
be774f3 Add my README with info about project
7aeb209 Add my module and the script that uses it
b96286f Add .gitignore
```

## Errors:

Ми намагаємось створити коміт, коли ще не додали змінені файли в зону підготовки, тому коміту нічого зберегти, треба
додати змінені файли

```Branch
(.venv) PS D:...homework-13\task1\py-15-git> git commit
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

Ми знаходимось не в папці репозиторію, де лежить _**.git**_, тому отримуємо помилку, треба зайти в репозиторій

```Branch
(.venv) PS D:...homework-13\task1> git status
fatal: not a git repository (or any of the parent directories): .git
```


