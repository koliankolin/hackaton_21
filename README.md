# Решение команды Command
### Фичи
1. В Native city, Heard about school from, Life status отдельная категория для Nan
2. Все Nan в днях, проектах и экзаменах вынесли в бинарные фичи, думая что Nan - это отсутствие регистрации
3. Contract termination date в бинарную фичу: есть дата или нету
4. По участникам: общее кол-во баллов, среднее отклонение, среднее и тоже самое по отсутствиям регистраций
5. Бинарная фича is_level_greater_4
6. Преобразование городов, чтобы уменьшить размерность
7. Возраст из даты рождения и преобразование даты в число

### Модель
Обычный LightGBM без оптимизации параметров
