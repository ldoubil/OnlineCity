Что бы бот начал работать, при запуске, необходимо указать секретный токен бота в качестве параметра и путь к базе данных.
После этого он создает, если не было пустую базу данных и начнет слушать все каналы.
Если в одном из каналов набирается команда
OC! Reg IP_Server:Port Bot_Token
То на данном канале регистрируется бот и начинает ретранслировать сообщения с указанного сервера Online City

Если вы хотите отправить сообщение в игру, для этого надо сперва зарегистрироваться:
набрать в ПРИВАТНОЕ сообщение боту: OC! RegMe MyToken
Бот сам найдет на каком сервере Online City есть пользователь с таким токеном и в каком канале разрешить ему писать сообщения.
Все не авторизированные сообщения с зарегистрованого канала будут автоматически удаляться ботом в избежании флуда.
Что бы узнать свой токен, наберите в игре команду /Discord
В ответ будет сообщен ваш токен, никому не говорите его, и регистрируйтесь только через приватный чат бота.
Как это будет выглядть в игре:
Discrord: UserLogin1: Hello world
Что бы узнать токен сервера Online City , наберите в игре комнду /Discord ServerToken
В ответ будет сообщен токен сервера, никому не говорите его, и регистрируйтесь сначала сделав приватный канал для чата на Discord,
После успешной регистрации сообщение –команда будет автоматически удалено и после этого можно открыть канал для всех.
Действуют следующие ограничения:
Один канал Discord - один сервер Online City

Если сервер недоступен более X минут, то тому человеку который его зарегистрировал отправляется приватное сообщение,
что сервер недоступен, и необходимо принять меры.

Зависимости:
.Net FrameWork 4.8 или старше
https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral
.Net Core Entity FrameWork 2.2.6
MySQL – 	GNU GPL v2
Discord.Net The MIT License (MIT)