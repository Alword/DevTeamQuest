# Направление "Тестирование"

## Введение
Для выполнения задания надо будет придумать как мы будем проверять работу ПО и немного поработать!

## План по написанию планов
Мы уже знаем, что мы будем тестировать. Данная информация позволяет нам сначала подумать над тем, как мы будем тестировать.
Поэтому перед тем, как тыкать на кнопки и записывать результат, мы должны разработать три артефакта тестирования (в общих чертах)

### Тест-стратегия
Стратегия отвечает на следующие вопросы: 
- какие техники тестирования мы будем применять (черный/белый ящик, негативно и позитивное тестирование и т.п.)
- Какие модули системы мы будем тестироваить
- Степень автоматизации процессов
- Ресурсы (серверы, кол-во человекочасов, инструменты)

Задача: Ответить на эти вопросы и зафиксировать их.
Задача*: Дополнить секцией "управление релизами" и "анализ рисков". 

### Тест-кейс
Тест-кейс помогает тестировщику проверить функционал и описывает требования в удобном для тестировании вида.
Состоит из следующих частей
- BeforeTest (шаги, которые необходимо выполнить перед началом тест-кейса)
- Steps (Сами шаги, которые необходимо выполнить, чтобы проверить функционал)
- AfterTest (Шаги, которые надо выполнить после завершения тест-кейса)
- (Severity/Priority) Приоритет тест-кейса. Зависит от важности проверяемого функционала для пользователей и системы. (помогает выбрать severity/priority при заведении дефекта)

Задача: Составить несколько тест-кейсов.
 
### Тест-план
План отвечает на следующие вопросы:
- какой функционал будет протестирован в этом релизе
- в какие сроки будет протестирован релиз
- какие ресурсы использованы в процессе тестирования

Задача: Ответить на эти вопросы и зафиксировать их.
Задача*: Подумать что надо тестировать в первую очередь, а что можно проверить в последнюю очередь. Вкратце описать.


## Опять работать
Поскольку у нас есть план и целая стратегия, то пора немного поработать: 
Для начала протыкайте ботов и проверьте их работу.
Если вам что-то кажется странным, то сформулируйте что вам не нравится. 
Спойлер: для этого напиши что идет не так, где появилась ошибка и при каких условиях она воспроизводится. 

P.s.
Фраза "Ничего не работает" оскорбляет чувства программирующих :)
 