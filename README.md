# ЮЗЕРБОТ СПАМЕР
**Юзербот-спамер**, написанный на **Pyrogram**. **Полная кастомизация**, установка времени работы спамера, интервал между отправкой сообщением. **Добавление текста или фото**.
---
## 🔎 Функционал
+ Установка текста и/или фото в сообщение
+ Установка времени работы спамера (в часах) и интервала отправки сообщений (в секундах)
+ Просмотр установленных данных (время работы, интервал, текст и/или фото)
+ Автоматические ожидание разблокировки API (бан за антифлуд)
+ Показ количества чатов, в которые будет отправлено сообщение
+ Показ итогового количества чатов, в которые сообщение было отправлено
---
## ⬇️ Установка
1. Установите необходимые библиотеки командой `pip install -r requirements.txt`
2. Зайдите на ([официальный сайт Telegram](https://my.telegram.org/apps)) для создания приложений и получите оттуда `API_ID & API_HASH`
3. Введите эти данные в файл `config.ini`, который находится рядом с `main.py`
4. Запустите `main.py` и следуйте дальнейшим инструкциям
---
## 📝 Управление спамером
+ `/start` — запускает спамер во все ваши чаты, перед началом нужно указать фото и/или текст рассылаемого сообщения
+ `/info` — выводит установленную информацию (время работы, интервал, текст и/или фото)
+ `/timer` `/timer 0 0` — устанавливает время работы спамера и интервал (после команды нужно указать два значения: 1 — время работы в часах, 12 — интервал в секундах)
+ `/text` `/text 0` — устанавливает текст для сообщения (поддерживается HTML-разметка, эмодзи и т.д)
+ `/photo` `/photo 0` — устанавливает фото для сообщения
---
> [!WARNING]
> Запуск спамера не совсем корректно работает, необходимо после команды `/start` отправить любое сообщение, тогда рассылка начнётся. Я пока не нашёл решение, как это фиксится :( 


