# Инструкция по работе с Git и удаленными репозиториями


## Что такое git?
Git-это одна из реализаций распределенных систем контроля версий, что позволяет иметь версионность как в локальном репозитории, так и в удалённом репозитории(общем для всех). Git является на данный момент самой популярной системой контроля версий.

## Подготовка репозитория

Для создания репозитрия используется кoманда git init

## Создание коммитов


### Просмотр состояния репозитория
Для просмотра состояния репозитория используется команда *git status*. Для этого необходимо в папке в терминале написать команду *git status* и возможно увидеть несколько состояний
1.Nothing to commit- репозиторий не содержит изменений
2.Unversioned file- папка содержит файл, к которому не добавлена версионность. 
### Добавление файла в коммит
Для добавления git add. В терминале с папкой текущего репозитория написать
## Перемещение между "сохранениями"
### Фиксация изменений
команда git commit - m "Сообщение писать обяз

## Журнал изменений



## Перемещение между  *сохранениями*
Для того чтобы перемещаться команда *git chechout <номер коммита>
## Ветки в git

## Слияние веток и решение конфликтов

## Удаление веток


## Отправка изменений в Git gubу
Для отправки изменений в удаленный репозиторий нужна команда git push. Для этого в терминале с папкой с репозиторием, связанным с удаленным репоиторием пишем команду *git push origin <название ветки>*, где название ветки- это ветка в удаленном репозитории куда нужно отправить
## Получение удаленного репозитория
Для того тобы скачать удаленный репозиторий необходимо использовать команду git clone. В терминале в котором открыта любая пустая папка, необходимо написать "git clone <ссылка на удаленный репозиторий. Удаленный (с Github) репозиторий скачается в папку, название которой будет совпадать названием репозитория.

## Скачивание  изменений с  удаленного репозитория
Для того чтобы скачать изменения нужна команда git pull. В терминале с папкой с репозиторием, связанным с удаленным репозиторием, пишем git pull origin <название ветки> для того, чтобы принять изменения из указанной ветки удаленного репозитория в текущую ветку.
