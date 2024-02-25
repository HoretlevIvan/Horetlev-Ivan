# создать и запустить виртуальное окружение

прописать в терминале python3 -m venv venv
source venv/bin/activate (Для пользователей Linux)
venv\Scripts\activate (Для пользователей Windows)

# Установить все необходимые для работы зависимости

pip install -r requirements.txt

# Запустить сервер в режиме dev

cd lyceum
python manage.py runserver
