### Модуль mymod.py з трьома функціями, які працюють зі списком текстових рядків, переданих як аргумент

- count_lines (lines) — кількість рядків.
- count_chars (lines) — загальна кількість символів.
- test (lines) — викликає обидві функції та виводить результати у зручному для читання форматі.

```python
# запуск скрипту: 
python
my_file.py
# через імпорт: 
mymod.test(["hello Ukraine", "city: Lvyiv", "'car brand: Skoda", "USA, Florida"])
```

> git status не показав pycache - тому що ми додали цю папку в gitignore, тому Git її ігнорує