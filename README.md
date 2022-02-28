# Описание 
Практическое задание курса ["Введение в Data Science и машинное обучение"](https://stepik.org/lesson/226979/step/2?unit=199528) от Stepik

В данном notebook проводится обучение модели на данных о пользователях курса Stepik с 2015 по 2018 год

Тестирование проводится на данных за первые два дня обучения пользователей, которые проходили курс в период с мая 2018 по январь 2019

Описание данных:

events_train.csv - данные о действиях, которые совершают студенты со стэпами

step_id - id стэпа
user_id - анонимизированный id юзера
timestamp - время наступления события в формате unix date
action - событие, возможные значения:
discovered - пользователь перешел на стэп
viewed - просмотр шага,
started_attempt - начало попытки решить шаг, ранее нужно было явно нажать на кнопку - начать решение, перед тем как приступить к решению практического шага
passed - удачное решение практического шага
submissions_train.csv - данные о времени и статусах сабмитов к практическим заданиям

step_id - id стэпа
timestamp - время отправки решения в формате unix date
submission_status - статус решения
user_id - анонимизированный id юзера
