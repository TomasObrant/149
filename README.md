docker-compose up -d

http://localhost:3100/ready - проверка готовности loki

http://localhost:3000 - admin/admin

http://localhost:3000/connections/datasources/new - ищем loki
поле Connection - http://loki:3100 
save&test 