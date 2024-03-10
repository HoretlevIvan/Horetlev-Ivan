# Иструкция

прописать в терминале python3 -m venv venv
source venv/bin/activate (Для пользователей Linux)
venv\Scripts\activate (Для пользователей Windows)

# Установить все необходимые для работы зависимости

pip install -r requirements.txt

# Запустить сервер в режиме dev

cd lyceum
python manage.py runserver

# Приступаем к скачивание всех необходимых библиотек (зависимости)

# Чтобы запустить проект прописываем:
pip install -r  requirements\test.txt

# Для разроботки проекта прописываем:
pip install -r  requirements\dev.txt

# Чтобы запустить сервер в dev-режиме:
cd lyceum
python manage.py runserver
