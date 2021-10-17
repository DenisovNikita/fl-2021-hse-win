# Проекты

Проекты индивидуальные, но типовые. Проект заключается в разработке конкретного синтаксиса языка по заданному абстрактному синтаксису (подробности в [ConcreteSyntax.md](tasks/ConcreteSyntax.md)), реализации для него синтаксического анализатора (подробности в [Parser.md](tasks/Parser.md)) и поддержки в среде разработки ((подробности в [IdeSupport.md](tasks/IdeSupport.md))).

Типовой проект на одного человека подразумевает реализацию или парсера, или поддержку в среде разработки. В случае выбора поддержки в среде разработки, должна быть реализована какая-нибудь нетривиальная фича (что-нибудь сложнее подсветки лексики).

Каждый участник должен выполнить нетривиальную часть проекта.

По результату проекта должен быть предоставлен отчет, в котором описано:

* В чем состояла задача
* Как вы ее решали. Например, какой и почему выбрали синтаксис, как парсили, как поддерживали в среде разработки.
* Какие сложности возникли и как их преодолели.
* Что конкретно сделал каждый человек из группы.


# Денисов
   * Типовой проект для языка [L](lang/L.md) + особенность синтаксиса 3.

# Запуск

   * Тесты находятся в папке [parser/tests/](parser/tests/). Сам парсер собран в бинарник parser/parser. Он принимает на вход один параметр --- путь до файла где находится тест. Скрипт [parser/run.sh](parser/run.sh) запускает все тесты. Для добавления тестов достаточно написать тест в файл и добавить его в папку tests/ с расширением .in.
