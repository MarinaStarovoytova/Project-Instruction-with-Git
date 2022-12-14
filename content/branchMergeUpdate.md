[//]: # ( ветвление и слияние )

[< Назад](/readme.md)

# Основные команды ветвления и слияния

`git checkout`

Команда git checkout может быть использована для создания веток или переключения между ними. К примеру, следующий код создаст новую ветку и переключится на нее:

    command git checkout -b <имя-ветки>

Чтобы просто переключиться между ветками:

    git checkout <имя-ветки>

`git branch`

Команда git branch может быть использована для отображения, создания или удаления веток. Для отображения всех существующих веток в репозитории введите:

    git branch

Для удаления ветки:

    git branch –d <имя-ветки>

`git merge`

Команда git merge используется для объединения ветки в активную ветвь. Применение:

    git merge <имя-ветки>

`git mergetool`

Команда git mergetool просто вызывает внешнюю программу слияний, в случае если у вас возникли проблемы слияния.

`git tag`

Используется для маркировки определенных коммитов с помощью простых меток. Примером может быть эта команда:

    git tag 1.1.0 <вставьте-commitID-здесь>

`git log`

Запуск команды git log отобразит список всех коммитов в ветке вместе с соответствующими сведениями.

`git stash`

Используется для временного сохранения всех незафиксированных изменений с целью очистки рабочего каталога без необходимости фиксировать незавершённую работу в текущей ветке. Применение:

    git stash
