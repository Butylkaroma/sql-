SELECT COUNT(*) AS TABLE_COUNT -показывает количество таблиц
SELECT TABLE_NAME FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE='BASE TABLE' - показывает названия всех таблиц
SELECT * FROM users; показывает всех пользователей
SELECT * FROM grades; показывает все оценки
SEKECT * FROM users,grades WHERE users.user_id=grades.user_id -запрос из двух таблиц (кто получил оценки)
