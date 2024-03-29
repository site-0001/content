---
title: 'LiveStreet'
portfolio:
  date: '2015-10-06'
  url: 'http://livestreet.ru'
---

Сначала мне очень не нравился LiveStreet CMS. Но потом я попробовал шаблон "Developer-Kit" от vOFFka на основе Bootstrap и с этим шаблоном LiveStreet для меня заиграл новыми красками. И так заиграл, что я выпустил для своих проектов и некоторое время поддерживал собственные модули и модификацию этого шаблона под названием "Developer-Kit MOD", в которой я исправлял ошибки в вёрстке и обновлял компоненты.

*Более подробную информацию можно посмотреть внутри карточки.*

<!--more-->

## Developer-Kit MOD

[Developer-Kit MOD](http://livestreet.ru/blog/18322.html) отличается от оригинала следующими параметрами:

- Чтобы не править оригинальную тему `default`, была создана новая - `system`.
- Добавлены иконки Font Awesome для верхней навигации и выпадающей панели пользователя.
- Добавлены кнопки обновления прямого эфира и списка блогов. В оригинальной версии эти кнопки отсутствуют.
- Twitter Bootstrap обновлён до версии `3.3.5`.
- Добавлена директория `custom/`, в которой располагаются дополнительные шаблоны.
- Код названия сайта вынесен в отдельный шаблон `sitename.tpl` и размещён в директории `custom/`.
- Статистика производительности отображается только для основного администратора с `ID = 1`.

{{< accordion-item "Другие изменения" >}}
Также в ходе разработки модифицированной версии были сделаны следующие изменения:

- Добавлен атрибут `alt="..."` для всех изображений. Атрибут имеет правильное содержимое (описание блога, логин пользователя и т.п.)
- Добавлены иконки для ссылок на популярные сетевые ресурсы.
- Исправлено название сайта. Теперь на главной странице название сайта помещается в тег `h1`, а при чтении топика помещается в теги `span`, потому что - заголовок топика уже в теге `h1`. Два тега `h1` на одной странице семантически неправильно.
- Откорректированные информационные сообщения.
- Тег `b` заменён на `strong`.
- Символ `&` заменён на его аналог `amp`.
- Символ `·` заменён на его аналог `middot`.
- Тег `small` убран. За место него используется класс `.small`.
- Изображения добавляемых материалов во всплывающем окне заменены на их аналоги из Font Awesome.
- Добавлены мета-теги разметки для социальных сетей в секцию `header`.
- Мета-теги социальных сетей разделены на отдельные файлы: для блога, для топика и для профиля пользователя. Эти файлы автоматически подключаются - в зависимости от страницы, на которой находится пользователь или поисковый робот.
- Исправлено отображение надписей кнопки "добавить в избранное". Раньше даже когда статья была уже добавлена в избранное, надпись "добавить в - избранное" всё равно отображалось. Теперь же есть две надписи "добавить в избранное" и "удалить из избранного". Надписи меняются в зависимости - от состояния кнопки.
- Шрифт в редакторе изменён на `sans-serif`. Monospace больше не используется.
- Страницы с отсутствующей боковой панелью теперь имеют максимальную ширину.

Введены дополнительные настройки и фразы. Настройки позволяют включать/отключать отображение таких элементов, как:

- ссылка входа;
- ссылка регистрации;
- блок со списком блогов;
- блок прямого эфира;
- блок со списком тегов;
- блок со списком стран;
- блок со списком городов;
- блок статистики;
- кнопки голосования пользователя;
- кнопки голосования блога;
- кнопки голосования топика;
- кнопки голосования комментария.

Так же присутствуют настройки, позволяющие задавать ссылки на страницы социальных сетей, вместо копания в шаблоне.
{{< /accordion-item >}}
