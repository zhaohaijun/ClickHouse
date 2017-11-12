Date
----

Дата. Хранится в двух байтах в виде (беззнакового) числа дней, прошедших от 1970-01-01. Позволяет хранить значения от чуть больше, чем начала unix-эпохи до верхнего порога, определяющегося константой на этапе компиляции (сейчас - до 2038 года, но может быть расширено до 2106 года).
Минимальное значение выводится как 0000-00-00.

Дата хранится без учёта часового пояса.