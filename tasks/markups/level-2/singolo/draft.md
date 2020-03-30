# Порядок сдачи

1. Внимательно ознакомьтесь с документом [„Cross Check Flow“](https://docs.rs.school/#/cross-check-flow).
2. Как можно раньше до дедлайна [отправьте свою работу на оценку в **RS App**](https://app.rs.school/course/student/cross-check-submit?course=rs-2020-q1). Без этого ее не смогут оценить, и вы получите **0**.  
3. Критерии оценки берём из текущего документа. Не из других. Не придумываем сами.

# Порядок проверки

Если выполняются основные условия, но есть недочеты не указаные в данном файле, их не учитываем.

## Подготовка

Ознакомиться с требованиями данного документа.

## Оценка

#### Если репозиторий singolo существует, и в нем есть index.html, style.css и script.js файлы, ставим **100** балоов. 

Если репозиторий отсуствует, значит задание не выполнялось, ставим **0**. Минимально возможный балл, также **0**. В минус результат уйти не может. 

#### Смотрим коммиты и ветки в репозитории.  
1. Если в коммитах, или в ветках с коммитами, файл script.js отсутствует до 22.03.2020, ставим **-10**.  
2. Если присутствуют коммиты, сделанные 29.03.2020 и позже, ставим **-5**.

#### Если найдены сторонние источники javaScript кода (библиотеки / фреймворки), ставим **-10**.
1. Сторонним источником счиатаеся js подключенный с помощью cdn, или по удаленному пути.  
2. Сторонним источником считается любой фреймворк, использованный в ходе разработки. Для этого нужно заглянуть в package.json, посмотреть какие фреймворки подключены.