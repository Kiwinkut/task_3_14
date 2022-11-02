## GIT ADD

**GIT ADD и GIT RM** — индексация изменений/

*Следующее, что нужно знать — команда git add. Она позволяет внести в индекс — временное хранилище — изменения, которые затем войдут в коммит.*

Индексирует измененный файл, либо оповещение о создании нового:
```
git add EDITEDFILE
```

Вносит в индекс все изменения, включая новые файлы:
```
git add .
```
Из индекса и дерева проекта одновременно файл можно удалить командой 
```
git rm.
```
Удаляет из индекса и дерева проекта отдельные файлы:
```
git rm FILE1 FILE2
```
Хороший пример удаления из документации к git, удаляются сразу все файлы txt из папки:
```
git rm Documentation/\*.txt
```
Вносит в индекс все удаленные файлы:
```
git rm -r --cached .
```
Сбросить весь индекс или удалить из него изменения определенного файла можно командой git reset:
```
git reset
```
Удаляет из индекса конкретный файл:
```
git reset — EDITEDFILE
```
Команда git reset используется не только для сбрасывания индекса, поэтому дальше ей будет уделено гораздо больше внимания.