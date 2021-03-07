Задача №1 - KeyValidator

Предыстория

Иногда, нам как тестировщикам, везёт - и мы получаем от разработчиков (программистов) уже готовый и настроенный испытательный стенд (машину, где мы можем выполнять функциональное тестирование).

Достаточно часто нам приходится с нуля устанавливать и настраивать необходимое окружение для приложения, и не потому, что у разработчиков нет времени, они ленивые или вредные smiling_imp, а потому что:

Нужно протестировать документацию
Нужно протестировать установку
Нужно протестировать совместимость
Поэтому вам нужно привыкать по готовым инструкциям устанавливать, настраивать и запускать ПО.

Легенда

Вы участвуете в Legacy (проект с унаследованным кодом), в котором есть небольшое приложение, проверяющее лицензионные ключи.

Приложение написано на языке Java (значит вам нужно установить Java) и работает из командной строки.

Что нужно проверить:

Инструкция по установке OpenJDK11 работает под вашу ОС
Приложение запускается и совместимо с Java 11
Приложение работает согласно руководству использования
Документация:

Инструкция по установке OpenJDK 11
Руководство использования
Подготовьте отчёт о проведённом тестировании в указанном формате и разместите его в репозитории.

Подсказка

Что-то мне подсказывает, что при копировании таких "длинных" серийных номеров кто-то мог ошибиться.

Итого: у вас должен быть репозиторий на GitHub, в котором расположен отчёт о проведённом тестировании и заведены баг-репорты в Issues (если баги есть).