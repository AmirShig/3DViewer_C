# 3DViewer v1.0
Программа для работы с каркасными моделями в трехмерном пространстве, разработанная на языке C с использованием структурного подхода к программированию. Поддерживает формат .obj для представления трехмерных объектов.

Основные действия:
Move: Перемещение объекта по трехмерному пространству с помощью кнопки "Move".

Size: Изменение размера объекта с использованием кнопки "Size".

Rotate: Вращение модели вокруг осей X, Y и Z с помощью кнопки "Rotate".

All Clean: Удаление .obj файла, если он загружен, при нажатии на кнопку "All Clean".

Set Default: Возврат объекта в исходное состояние по кнопке "Set Default".

# Настройка графического интерфейса:
Программа предоставляет графический интерфейс пользователя с элементами управления для загрузки, настройки и визуализации моделей. Пользователь может настроить:

Тип ребер (сплошная, пунктирная), цвет и толщину ребер.

Способ отображения вершин (отсутствует, круг, квадрат), цвет и размер вершин.

Цвет фона.

Настройки сохраняются между перезапусками приложения.

# Запуск приложения:
Запуск производится с использованием Makefile.

Цели Makefile включают:

all: Выполнение всех целей ниже.

install: Сборка программы и размещение в директории "build".

uninstall: Удаление директории "build".

clean: Удаление исполняемых файлов.

dvi: Открытие файла с описанием программы в формате .md.

dist: Архивирование проекта с расширением .tgz.

test: Запуск тестов для проверки корректности работы программы.

gcov_report: Отображение покрытия программы тестами.

Дополнительно:

Чтобы открыть файл, нажмите кнопку "Open file", выберите папку, содержащую ваш объект, и выберите его. Важно, чтобы файл имел расширение .obj.

Пользователь может создать gif-файл, нажав на кнопку "Create gif".
