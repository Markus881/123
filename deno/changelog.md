# 1.0.2
- Добавлен `/heath` эндпоинт
- Добавлен номер версии в конфиг

# 1.0.1
- Исправление заголовков ответа (фикс проксирования аудио) в #1

# 1.0.0
- Продублирован весь функционал Cloudflare Worker в Deno Worker
  - Проксирование запросов на перевод видео (/video-translation)
  - Проксирование запросов на перевод стримов (/stream-translation)
  - Проксирование запросов на получение субтитров (/video-subtitles)