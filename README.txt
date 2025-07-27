
Aztek Tex-Mex — Telegram Mini App + WebApp
===========================================

📦 Как развернуть:

1. Перейди на https://vercel.com/
2. Зарегистрируйся или войди
3. Нажми "Add New" → "Project" → "Import"
4. Залей все файлы из этого архива
5. При выборе:
   - Framework Preset: Other
   - Output Directory: оставить пустым
   - Build Command: не указывать
6. Нажми Deploy

🔗 Получишь ссылку типа https://aztek.vercel.app

📱 Как подключить к Telegram:

1. Зайди в @BotFather
2. Выбери своего бота → Edit Bot → Edit Commands → вставь:
   /start - меню
3. Зайди в "Edit Bot" → "Menu Button" → Web App:
   {
     "type": "web_app",
     "text": "🍽 Меню",
     "web_app": {
       "url": "https://ваш-сайт.vercel.app"
     }
   }

📩 Заказ придет в Telegram-аккаунт с ID 7903538631

📌 Язык переключается вверху: RU/PL
📌 В меню 6-8 позиций с фото, ценами, описанием
📌 Под каждой — кнопка “Добавить”, снизу — корзина

Сделано для мобильной версии Telegram Mini App
