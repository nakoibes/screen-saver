# ScreenSaver
Это приложение иммитирующая движение множества точек по экрану. Проект использует Python3.9

# Функционал:
1. При нажатии на экран рисуется точка
2. Когда на экране больше 2 точек, рисуется узел
3. При нажатии P точки и узлы приходят в движение
4. Num+, Num- - добавление и удаление точек сглаживания в текущий узел(меньше точек сглаживания - боольше похоже на ломаную)
5. F,S - ускорить или замедлить движение текущего узла
6. F1 - открыть справку
7. N - создать новый узел
8. 1,2,3 - переключиться на соответствующий узел
9. R - перезагрузить приложение

# Установка:
1. Склонировать репозиторий 
2. Создать виртуальное окружение `virtualenv venv -p python3.9`
3. Активировать виртуальную среду `source venv/bin/activate`
4. Установить зависимости `pip install -r requirements.txt`
5. Запустить приложение `python main.py`
