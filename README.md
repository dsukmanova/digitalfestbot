# Digitalfest-bot
Бот фестиваля цифровых технологий для школьников http://digitalfest.ru/

Игровой бот позволяет участникам конференции (детям и родителям) узнавать расписание ближайших лекций,
мастер-классов и игр в игровых зонах. Кроме того участники могут получать на каждой локации кодовые слова, 
бот будет их проверять и начислять участнику очки.
По окончании конференции бот проводит опрос о том, понравилось ли мероприятие и предлагает посетить курсы организации.

Бот строит расписание на основании таблички, заданной в гуглдоке.

##Для успешного запуска:
*все настройки собраны в файле config.properties
*скрипты создания базы данных в папке db
*в корень необходимо добавить папку config, в ней файл google-api-key.secret - ключ, созданный через google-api для корректной работы с googlesheets

**перепетии с запретом использования Телеграм никак не учитываются в данном проекте :(
