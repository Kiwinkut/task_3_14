## GIT DIFF
[Назад](./readme.md)

**GIT DIFF** — отличия между деревьями проекта, коммитами и т.д.
Своего рода подмножеством команды git log можно считать команду git diff, определяющую изменения между объектами в проекте - деревьями (файлов и директорий).

Показывает изменения, не внесенные в индекс:

git diff
Изменения, внесенные в индекс:

git diff --cached
Изменения в проекте по сравнению с последним коммитом:

git diff HEAD
Предпоследним коммитом:

git diff HEAD^
Можно сравнивать «головы» веток:

git diff master..experimental
или активную ветку с какой-либо:

git diff experimental
