# Телеграм Бот с Реплицируемой Базой Данных в docker compose

## Возможности

- **Мониторинг Системы по SSH**: Мониторинг Linux систем с использованием доступных команд.
- **Анализ Текста**: Поиск номеров телефонов и электронных адресов в тексте .
- **Проверка Сложности Паролей**
- **Интеграция с Базой Данных**: Просмотр содержимого таблиц с возможность добавления найденных номеров телефонов и электронных адресов в базу данных.
- **Репликация**: Обеспечение репликации данных между несколькими экземплярами базы данных.


### Чтобы развернуть проект с помощью docker, необходимо :
1. скачать репозиторий командой git clone "https://github.com/ArslanValeev/Docker.git . "
2. установить docker, docker compose
3. заполнить .env файл вашими данными (**важно: не меняйте хосты для бд и реплики, т.к. они настроены на докере**), в нем необходимо указать
   токен, данные удаленного хоста.
4. собрать проект командой "docker compose up"



