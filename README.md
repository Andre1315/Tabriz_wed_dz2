Садат Саид Табриз, БИС-231. Web-программирование II.

В папках 01–09 находятся решения девяти домашних заданий. Нумерация упражнений сохранена. Звёздочка в именах папок Fastify заменена на `_extra`, поскольку Windows не допускает `*` в имени файла.

Для общей проверки нужны Node.js 20+, Python 3.11+, PostgreSQL 16, curl и HTTPie. Настройка учебных баз описана в README папок 05, 07 и 08.

```sh
npm install
python -m pip install -r requirements.txt
npx playwright install chromium
npm test
```

Один раздел можно проверить командой `node check.mjs --group=01_react`. Отдельные упражнения запускаются по своим README.
