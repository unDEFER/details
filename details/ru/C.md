# @CaseCommand

Команда case в Bash позволяет сравнить строку с несколькими значениями.
При этом одно и тоже поведение при совпадении с разными строками
обеспечивается символом логического "ИЛИ" `|`. А сравнение с произвольной
строкой звёздочкой `*`.

# @CheckEmptyString

Конструкция `[ -z "строка" ]` аналогична команде `test -z "строка"`
и возвращает ноль (признак успешного выполнения) в случае если строка пуста.

`man test` для подробностей какие ещё проверки умеет делать test.

# @CheckUtilities

Bash обеспечивает базовые функции для создания логики скрипта, однако
основное дело делают в нём обычно другие программы. Мы проверяем
наличие необходимых нам программ, т.к иначе скрипт всё равно упадёт,
но с некрасивой ошибкой.

# @ColorsInBash

Чтобы сделать вывод в Bash цветным можно использовать контрольные символы
терминала. 

Так последовательность `\x1B[1;37m` переключает цвет вывода на ярко-белый
(во всяком случае для терминала с тёмной цветовой схемой,
 работу скрипта в белом терминале я не проверял).
А `\x1B[1;0m` переключает цвет вывода обратно.
