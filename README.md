# The_final_Yandex_Practicum_project
# Тесты на проверку создание заказа и получение данных заказа с помощью API Яндекс Самокат.
- Для запуска тестов должны быть установлены пакеты pytest и requests
- Запуск всех тестов выполянется командой pytest
- после запуска сервера его url должен быть внесён в файл configuration.py в следующую строку:
URL_SERVICE = "скопируй сюда URL, который у тебя сгенерировался без слеша в конце"
 
- Шаги автотеста
1. Выполнить запрос на создание заказа.
2. Сохранить номер трека заказа.
3. Выполнить запрос на получения заказа по треку заказа.
4. Проверить, что код ответа равен 200.
