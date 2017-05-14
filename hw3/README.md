## Сложный вариант

# Задача: необходимо реализовать игру в пятнашки.
# Задача про пятнашки действительно непростая, но очень интересная.
# Требования:
# Игра пятнашки: https://ru.wikipedia.org/wiki/%D0%98%D0%B3%D1%80%D0%B0_%D0%B2_15
# Поле состоит из клеток от 1 до 15 и пустой клетки
# Управление ведется кнопками "wasd", двигается пустая клетка
# В начале игры поле перемешено в случайном порядке
# Пользователь не должен соверашть непозволительные шаги. Например, из-за ограничений рамки поля. Ему должно показываться сообщение о том, что он пытается совершить непозволительный ход
# Пользователю дожно быть видно поле. Оно представляет собой матрицу 4 на 4. Пустую клекту обозначаем как x. При каждом действии пользователя поле рисуется еще раз - ниже в консоли
# Игра заканчивается, когда все клетки стоят по-порядку, а пустая клетка - последняя. В конце игры пользователю показывается, сколько ходов он совершил
# Выход из игры происходит при помощи KeyboardInterrupt. Исключение должно быть обработано. Пользователю должна быть выведена фраза "shutting down"
# Технические требования:
# Игра должна соответствовать интерфейсу из файла game.py. Под "соотвествовать интерфейсу" следует понимать: программа может иметь только те константы и функции, что уже опеределены, сам файл должен называться: game.py. Внутри реализуемых функций может происходить любая логика
# Дополнительно:
# Обратите внимание, что не любое поле оставляет возможность закончить игру, необходимо придумать корректный алгоритм генерации взамен простого перемешивания
# Тесты, которые приложены к работе должны проходить
# Вам необходимо посмотреть, как работают самописные тесты, которые приложены к работе
# Прохождение тестов:
# Создаем папку game_code
# В ней создаем файл game.py
# Рядом должен лежать мой файл tests.py
# Вызываем python3 tests.py