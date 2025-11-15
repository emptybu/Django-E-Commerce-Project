# Django-E-Commerce-Project

## Описание

Современный интернет-магазин на Django с системой пользователей, каталогом товаров и корзиной покупок.

**Основной функционал:**
- Система аутентификации и авторизации
- Корзина покупок и избранное
- Управление товарами и категориями
- Интеграция с платежными системами
- Поиск и фильтрация товаров

## Зависимости

| Пакет | Версия | Назначение |
|-------|--------|------------|
| Django | 4.2.7 | Основной фреймворк |
| django-crispy-forms | 2.0 | Стилизация форм |
| Pillow | 10.0.0 | Обработка изображений |
| psycopg2-binary | 2.9.7 | PostgreSQL драйвер |
| whitenoise | 6.5.0 | Статические файлы |
| gunicorn | 21.2.0 | Production сервер |

## Установка и настройка

### Настройка виртуального окружения

bash
# Клонирование репозитория
git clone https://github.com/your-username/django-ecommerce.git
cd django-ecommerce

# Создание виртуального окружения
python -m venv venv

# Активация (Linux/Mac)
source venv/bin/activate

# Активация (Windows)
venv\Scripts\activate

# Установка зависимостей
pip install -r requirements.txt

## Инструкции по запуску миграций и сервера.
'''python manage.py makemigrations manage.py migrate manage.py createsuperuser '''
