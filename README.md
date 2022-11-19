# LR6
## Лабораторная работа №6
- Была создана копия репозитория в личное хранилище (Fork).

![](https://github.com/regina7856/LR6/blob/report/screens/1.jpg)

- С помощью команд `git config --global user.name` и `git config --global user.email` производим первоначальную настройку Git: устанавливаем имя пользователя и электронную почту.

![](https://github.com/regina7856/LR6/blob/report/screens/2.jpg)
![](https://github.com/regina7856/LR6/blob/report/screens/3.jpg)

- Производится клонирование личного удалённого репозитория на компьютер с помощью команды `git clone`.

![](https://github.com/regina7856/LR6/blob/report/screens/4.jpg)

- Создаётся новый файл через интерфейс GitHub

![](https://github.com/regina7856/LR6/blob/report/screens/5.jpg)

- Переходим в локальный репозиторий командой `cd` и подтягиваем изменения командой `git pull`.

![](https://github.com/regina7856/LR6/blob/report/screens/6.jpg)
![](https://github.com/regina7856/LR6/blob/report/screens/7.jpg)

- С помощью команды `git log` получаем историю операций для ветки master

![](https://github.com/regina7856/LR6/blob/report/screens/8.jpg)

- Той же командой но с флагом `-p` для отображения в логе изменений

![](https://github.com/regina7856/LR6/blob/report/screens/9.jpg)

- Переходим на вторичную ветку (branch1) с помощью команды `git checkout branch1`

![](https://github.com/regina7856/LR6/blob/report/screens/10.jpg)

- Просматриваем историю операций и изменений.

![](https://github.com/regina7856/LR6/blob/report/screens/11.jpg)
![](https://github.com/regina7856/LR6/blob/report/screens/12.jpg)

- С помощью команды `git merge` из ветки мастер производится слияние ветки branch1 в мастер

![](https://github.com/regina7856/LR6/blob/report/screens/13.jpg)

- Действие привело к ошибке. Вводится команда `git status` для выявления конфликта

![](https://github.com/regina7856/LR6/blob/report/screens/14.jpg)

- Согласно рекомендации консоли исправляем конфликт добавлением файла в реестр
- Проверка с помощью `git status`. Конфликт был разрешён

![](https://github.com/regina7856/LR6/blob/report/screens/15.jpg)

- Делается коммит командой `git commit -m` (флаг `-m` позволяет закоммитить файл прямо из консоли, минуя текстовый редактор)

![](https://github.com/regina7856/LR6/blob/report/screens/16.jpg)

