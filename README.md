﻿# Проект frontend2step

## Запуск сборки проекта
В адресе вашего проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и разместите в нее папку вашего проекта. У вас может получится что то похожее на это: C:\projects\fsd_frontend2step

1. Клонирование проекта к себе на ПК               
```sh
git clone github.com/ragimoff/frontend2step.git
```

2. Переходим в созданную папку
```sh
cd frontend2step
```

3. Устанавливаем все зависимости
```sh 
npm install
```

### code guide

Соглашение по написанию кода. Общие правила которых будут придерживаться все члены команды:

* [less] - CSS препроцессор
* [Flexbox] - Для построения структуры страниц спользуем флексы
* [Bootstrap grid 4] - В сборке уже есть сетка от bootstrap-4
* [Табы] - Проверьте, что бы настройки отступов в редакторе были сделаны табами (это важно для PUG файлов)
* [Bem] - При написании кода используем BEM naming (Блок, Элемент, Модификатор)