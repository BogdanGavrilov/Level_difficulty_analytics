# Game analytics. Level difficulty detection.

Имеется DataFrame (https://drive.google.com/file/d/1Fg3bvX2NOzd3pqcEkH8-epbZFll60-36) со статистикой игровой активности пользователей в игре жанра match3. Данная таблица содержит лог событий за определенный промежуток времени по первым 500 уровням в игре.

Входные данные:

uid — уникальный id игрока;

action — ‘completed’ для успешной попытки прохождения уровня, ‘failed’ для неуспешной;

level — уровень, на котором произошло событие;

event_time — event_time/1000 является unix timestamp времени получения события.

На основе представленных данных можно выявить "проблемные" уровни для пользователей нашей игры. Также было бы неплохо расчитать "воронку" прохождения уровней новым пользователем после установки игры

Исследование находится в файле "Level_difficulty_analytics.ipynb".
