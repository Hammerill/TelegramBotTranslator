# TelegramBotTranslator
Телеграм бот написанный на C#, который переводит текст с английского на русский и обратно, используя GoogleAPI.



Установка и запуск
========================

1. Убедитесь, что вы скопировали репозиторий себе, а затем в корне репозитория откройте файл "default_botsettings.json", где вставьте параметр "tokenString", содержащий токен вашего бота, выданный t.me/BotFather.
2. Переименуйте файл "default_botsettings.json" в "botsettings.json".
3. Откройте sln файл при помощи Visual Studio и запустите проект, скомпилировав его.



Планы на будущее
========================

1. Реализовать возможность переключения между всеми языками, доступными в GoogleAPI (логика смены языков для пользователей уже прописана, осталось добавить эту возможность в интерфейс бота).
