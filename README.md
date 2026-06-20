# Git Branching Homework

## Описание проекта
Проект для отработки ветвления в Git. Включает модули профиля, дисциплин и отчёта.

## Использованные ветки
| Ветка | Что делал | Как попала в main |
|-------|-----------|-------------------|
| feature/profile | модуль профиля | merge локально |
| feature/subjects | список дисциплин | merge локально |
| feature/report | итоговый отчёт | Pull Request |
| experiment/broken-idea | тестовая идея | удалена без merge |

## Pull Request
Ссылка на PR: https://github.com/4youmans/git-branching-homework-payusov/pull/1

## Коммиты
1. feat: добавить базовый запуск приложения
2. feat(profile): добавить модуль профиля студента
3. feat(profile): подключить профиль в main.py
4. feat(subjects): добавить модуль со списком дисциплин
5. feat(subjects): подключить список дисциплин в main.py
6. feat(report): добавить модуль генерации отчёта
7. feat(report): подключить отчёт в main.py
8. chore(experiment): добавить тестовую идею (ветка удалена)

## Скриншоты
- [Граф веток до merge](docs/screenshots/01-branches-before-merge.png.png)
- [Результат merge](docs/screenshots/02-merge-result.png.png)
- [Pull Request создан и слит](docs/screenshots/03-pull-request-merged.png.png)
- [Финальная ветка main на GitHub](docs/screenshots/04-final-github-main.png.png)

## Вывод
В ходе работы я научился создавать отдельные ветки для каждой функции, сливать их через merge и Pull Request. Понял, что ветка main всегда должна содержать рабочую версию, а экспериментальные идеи можно изолировать и удалять.