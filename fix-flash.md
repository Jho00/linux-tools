- вставляем флешку, запускаем терминал
- смотрим куда смонтирована флешка df -Th
- запускаем проверку с помощью dosfsck /dev/<имя_устройства> (например dosfsck /dev/sde1)
- если спрашивает действие, выбираем 1) Remove dirty bits
- на perform changes? пишем y и нажимаем Enter
- извлекаем флешку, вставляем снова
