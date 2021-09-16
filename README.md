# Домашнее задание к лекции 6.«Tests»

### Задача №1 unit-tests
Из курса «Python: программирование на каждый день и сверхбыстрое прототипирование» необходимо протестировать программу по работе с бухгалтерией [Лекции 2.1](https://github.com/netology-code/py-homework-basic/tree/master/2.1.functions).
При наличии своего решения данной задачи можно использовать его или использовать предложенный код в директории scr текущего задания.

* Следует протестировать основные функции по получению информации о документах, добавлении и удалении элементов из словаря.
  
Рекомендации по тестам.
1. Если у вас в функциях информация выводилась(print), то теперь её лучше возвращать(return) чтобы можно было протестировать.
2. input можно "замокать" с помощью ```unittest.mock.patch```, если с этим будут проблемы, то лучше переписать функции так, чтобы данные приходили через параметры.

### [Решение 1 unittest](unittest_.py)

### [Решение 1 pytest](pytest_.py)


### Задача №2 Автотест API Яндекса
Проверим правильность работы Яндекс.Диск REST API. Написать тесты, проверяющий создание папки на Диске.  
Используя библиотеку requests напишите unit-test на верный ответ и возможные отрицательные тесты на ответы с ошибкой

Пример положительных тестов:
* Код ответа соответствует 200.
* Результат создания папки - папка появилась в списке файлов.

### [Решение 2 unittest](yandex_test.py)

### Задача №3. Дополнительная (не обязательная)
Применив selenium, напишите unit-test для авторизации на Яндексе по url: https://passport.yandex.ru/auth/

### [Решение 3 unittest](selenium_test.py)
