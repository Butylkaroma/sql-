Шветко Роман 021 группа

SELECT COUNT(*) AS TABLE_COUNT - Показывает сколько таблиц

SELECT TABLE_NAME FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE='BASE TABLE' - Название всех таблиц

SELECT * FROM users; Показывает пользователей

SELECT * FROM grades; Показыает все оценки

SEKECT * FROM users,grades WHERE users.user_id=grades.user_id -Кто получил оценки
