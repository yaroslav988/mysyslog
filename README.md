# mysyslog

Проект mysyslog - это библиотека для логирования данных.

## Сборка проекта с помощью Makefile
- 'make all': собирает все цели.
- 'make clean': удаляет все временные файлы.
- 'make deb': собирает deb-пакет.

## Использование
- **mysyslog client**: запуск клиентского приложения: ./mysyslog-client -m "test message" -l INFO -d text -f /var/log/mysyslog.log
- **mysyslog daemon**: настройка конфигурации в '/etc/mysyslog/mysyslog.cfg' и запуск демона: sudo systemctl start mysyslog-daemon

