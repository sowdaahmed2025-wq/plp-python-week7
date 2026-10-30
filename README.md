# Week 7 Assignment: Shopping List Manager

- `list_warmup.py` - practises lists with index access, append, remove and len().
- `shopping_list.py` - a menu-driven shopping list manager with add, remove, show and done.
- `list_report.py` - loops through a list to print it numbered, count long names and find the longest.
- `screenshots/` - screenshots of each program running.

**Why is it safer to check `in` before calling `.remove()`?**
If you call `.remove()` on an item that is not in the list, Python raises a ValueError and the program crashes. Checking with `in` first lets the program print a friendly message and keep running instead.