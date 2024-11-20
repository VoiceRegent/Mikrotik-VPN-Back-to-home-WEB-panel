# Mikrotik VPN Back to home WEB panel


Этот инструмент позволяет управлять пользователями на устройстве Mikrotik через веб-интерфейс, созданный с использованием Gradio. Инструмент поддерживает регистрацию новых пользователей, управление существующими пользователями, генерацию паролей и настройку параметров подключения.

## Функциональность

- **Регистрация пользователей**: Добавление новых пользователей с указанием даты деактивации, расположения и имени.
- **Управление пользователями**: Получение списка пользователей, удаление пользователей, переключение состояния пользователей (активация/деактивация), выгрузка конфигурации пользователя.
- **Генератор паролей**: Генерация паролей с настраиваемыми параметрами (длина, использование заглавных букв, цифр, специальных символов).
- **Настройки**: Обновление параметров подключения (IP-адрес, порт, пароль).

## Установка

**Клонируйте репозиторий**:

`git clone https://github.com/your-username/Mikrotik-VPN-Back-to-home-WEB-panel.git`


2. **Отредактируйте const.py**

## Зависимости

Для работы этого инструмента требуются следующие внешние библиотеки:

- `routeros_ssh_connector`: Библиотека для подключения к устройству Mikrotik через SSH.
- `gradio`: Библиотека для создания веб-интерфейсов.
- `Python 3.10.0`

## Использование

1. **Запустите приложение**:
    ```sh
    RUN.BAT
    ```
2. **Введите логин и пароль в открывшемся окне браузера**:
    ```sh
    Логин: Admin
    Пароль: P@ssw0rd
    ```
    

## Настройка

Параметры подключения (IP-адрес, порт, пароль) можно изменить через вкладку "Настройки" в веб-интерфейсе.

## Логирование

Логи сохраняются в файл `watchdog.log`. Уровень логирования установлен на `INFO`.

## Лицензия

Этот проект лицензирован под ([MIT License](https://github.com/VoiceRegent/Mikrotik-VPN-Back-to-home-WEB-panel/blob/main/LICENSE.md))

## Автор

© 2024 Regent'sVoice.
