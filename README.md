# DigitalIntelligence
job placement test (JAICP DSL + JavaScript) Telegram bot

Перенес проект со своего второго аккаунта, поэтому одним коммитом. Так как в условиях тестового задания было предоставление токена со всеми правами.

Задание:
Разработать на платформе Just AI Conversational platform чатбота, умеющего играть в игру "Быки и коровы".

Игра рассчитана на двух игроков (пользователь и чатбот). Чатбот задумывает тайное 4-значное число с неповторяющимися цифрами. Пользователь делает первую попытку отгадать число. Попытка — это 4-значное число с неповторяющимися цифрами, сообщаемое чатботу. Чатбот сообщает в ответ, сколько цифр угадано без совпадения с их позициями в тайном числе (то есть количество коров) и сколько угадано вплоть до позиции в тайном числе (то есть количество быков). Например:

Задумано чатботом тайное число «3219».

Попытка: «2310».

Результат: две «коровы» (две цифры: «2» и «3» — угаданы на неверных позициях) и один «бык» (одна цифра «1» угадана вплоть до позиции).

Инструкция:
1. Зарегистрируйтесь в платформе Just AI Conversational Platform - https://app.jaicp.com/login (используйте форму регистрации, не “вход через”).
Сообщите нам почту, под которой вы создадите аккаунт.
2. В разделе пользователи предоставьте доступ пользователю (ФИ, логин присвойте любые) с правами Admin.
Сообщите нам данные (логин/пароль) созданного пользователя.
3. Зарегистрируйтесь на github.com. Создайте репозиторий (c доступами по токену https://help.just-ai.com/docs/ru/security/github_access_token) и предоставьте к нему доступ пользователю ss@digintel.ru (полный доступ).
4. Создайте на платформе проект, размещение проекта - в созданном репозитории.
5. В созданном проекте напишите сценарий чатбота, играющего в "Быки и коровы".
Все инструкции по работе с платформой размещены в Хелпе: https://help.just-ai.com/

Поправки:
1. Нужны автотесты на полный функционал
2. Нужно переписать код используя функции, отдельный файл и избавиться от лишних переменных в коде
3. В ответе бота о результате проверки нужно предусмотреть варианты отсутствия коров/быков и одной коровы/быка (сейчас текстовка подразумевает от 1 попадания)
4. Можно доработать бота и указывать количество попыток у пользователя для того, чтобы угадать число

Результат: Отказ.
"Не деполится, Очень много лишних переменных,много бесполезной работы"
(во фрагменте кода была допущена ошибка с отступом, поэтому проект не деплоился)
