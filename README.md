Данное приложение представляет собой компилятор с работающий сканером и парсером, реализованный с помощью Windows Forms на языке C#. Ниже подробно описаны все функции, доступные пользователю.

Меню "Файл"

    Создать документ – Очищает текущее текстовое поле и начинает работу с новым пустым документом. При этом сбрасывается предыдущий путь к файлу.
    Открыть документ – Позволяет выбрать и загрузить существующий текстовый файл (.txt) в редактор для дальнейшего редактирования.
    Сохранить документ – Сохраняет текущие изменения в уже открытом файле. Если документ новый, предлагается выбрать имя и место сохранения.
    Сохранить как – Открывает диалоговое окно для сохранения документа под новым именем или в другом месте.
    Выход – Завершает работу приложения.

Меню "Правка"

    Отменить (Undo) – Отменяет последнее выполненное действие, позволяя вернуться к предыдущему состоянию текста.
    Повторить (Redo) – Повторяет последнее отменённое действие, восстанавливая изменения.
    Копировать – Копирует выделенный текст в буфер обмена для последующей вставки.
    Вырезать – Удаляет выделенный текст из документа, сохраняя его в буфер обмена.
    Вставить – Вставляет текст из буфера обмена в текущую позицию курсора.
    Удалить – Удаляет выделенный текст без помещения его в буфер обмена.
    Выделить всё – Выделяет весь текст в документе для дальнейших операций (копирования, удаления и т.д.).

Меню "Справка"

    Вызов справки – Открывает данную HTML-страницу с подробным описанием функционала приложения.
    О программе – Выводит информацию о приложении, включая его название, версию, данные об авторе и копирайте.

Панель инструментов (ToolStrip)

    Создание документа – Быстрый доступ к функции создания нового документа (аналог пункта меню "Создать документ").
    Открытие документа – Позволяет быстро открыть существующий текстовый файл, аналогично функции из меню "Открыть документ".
    Сохранение изменений – Сохраняет текущие изменения в документе, эквивалентно пункту меню "Сохранить документ".
    Отмена изменений – Отменяет последнее действие (аналог функции "Отменить").
    Повтор последнего изменения – Повторяет отменённое действие (аналог функции "Повторить").
    Копировать текстовый фрагмент – Копирует выделенный фрагмент текста в буфер обмена (функция "Копировать").
    Вырезать текстовый фрагмент – Вырезает выделенный текст, сохраняя его для возможной вставки (функция "Вырезать").
    Вставить текстовый фрагмент – Вставляет текст из буфера обмена в документ (функция "Вставить").
    Запуск синтаксического анализатора – Кнопка предназначена для запуска синтаксического анализатора кода. На данном этапе функциональность не реализована и кнопка не выполняет никаких действий.
    Вызов справки – Позволяет вызвать справочную систему, открывая данную HTML-страницу с описанием функций.
    Вызов информации о программе – Отображает сведения о приложении, аналогично функции "О программе" в меню.

Диаграмма состояний:

![схема строки](https://github.com/user-attachments/assets/193b2642-e414-4123-aa49-7ac09c494c40)
