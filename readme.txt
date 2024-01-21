1. Создал виртуальную машину, установил CentOS 8.
2. Открыл на Firewall необходимые порты.
3. Установил PHP-FPM.
4. Установил Nginx, настроил виртуальный хост.
5. Установил Mysql, создал БД, пользователя.
6. Загрузил CMS WordPress.
7. Установил Prometheus, добавил в автозапуск.
8. Установил Alertmanager, добавил в автозапуск.
9. Установил Node_exporter, добавил в автозапуск, добавил в prometheus.yml
10. Установил Mysqld_exporter, добавил в автозапуск, добавил в prometheus.yaml
11. Установил Blackbox_exporte, добавил в автозапуск, добавил в prometheus.yml
12. создал алерт правила alert.rules.yml ослеживает состояние инстансов, services.rules.yml 
    отслеживает состояние сервисов. Добавил в prometheus.yml
13. прописал в prometheus.yml ссылку на Alertmanager для передачи алерта из Prometheus в Alertmanager.

