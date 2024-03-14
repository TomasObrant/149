http://localhost:3100/ready - проверка готовности loki

# первое подключение
http://localhost:3000 - admin/admin
http://localhost:3000/connections/datasources/new - ищем loki
поле Connection - http://loki:3100 

# мониторинг
http://localhost:3000/explore
Справа выбираем режим "code"
{filename="/var/log/auth.log"}
{job="varlogs"}

# отправка через http 
https://www.unixtimestamp.com/index.php - даты для файла log.http

http://localhost:3000/dashboard - выбираем loki
{label="test"}
