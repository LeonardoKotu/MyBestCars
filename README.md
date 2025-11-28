# 🚗 MyBestCars - Автомобильная платформа

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.3+-000000?logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

## 📖 О проекте

**MyBestCars** - современная веб-платформа для автолюбителей с удобным поиском и сравнением автомобилей.

### 🎯 Основные возможности
- 🔍 **Умный поиск** по параметрам
- 📊 **Сравнение характеристик** 
- ⭐ **Система избранного**
- 👥 **Отзывы и рейтинги**
- 📱 **Адаптивный дизайн**

## 🛠 Технологии

### Backend
- **Python 3.9+** - основной язык
- **Flask** - веб-фреймворк
- **Flask-WTF** - формы
- **SQLAlchemy** - ORM
- **PostgreSQL** - база данных

### Frontend
- **HTML5/CSS3** - верстка
- **JavaScript** - интерактивность
- **Jinja2** - шаблоны

## 🎨 Интерфейс

### Форма авторизации
```html
<div class="auth-form">
    <div class="logo">
        <i class="fas fa-car"></i>
        <span>MyBestCars</span>
    </div>
    <form>
        <input type="text" placeholder="Имя пользователя">
        <input type="password" placeholder="Пароль">
        <button>Войти</button>
    </form>
</div>
```

### Карточка автомобиля
```html
<div class="car-card">
    <img src="car.jpg" alt="BMW M5">
    <h3>BMW M5 Competition</h3>
    <div class="specs">
        <span>625 л.с.</span>
        <span>3.3 сек</span>
        <span>$120,000</span>
    </div>
</div>
```

## 📊 Виджеты

### Статистика
| Параметр | Значение |
|----------|----------|
| Мощность | 625 л.с. |
| Разгон 0-100 | 3.3 сек |
| Цена | $120,000 |

### Сравнение моделей
| Модель | Мощность | Цена |
|--------|----------|------|
| BMW M5 | 625 л.с. | $120k |
| Audi RS7 | 600 л.с. | $115k |

## 🚀 Быстрый старт

```bash
# Установка
git clone https://github.com/yourusername/mybestcars.git
cd mybestcars

pip install -r requirements.txt
flask db upgrade
flask run
```

## 📞 Контакты

<div align="center">

**Telegram:** [@excelvpotoke](https://t.me/excelvpotoke)

[![Telegram](https://img.shields.io/badge/Telegram-@excelvpotoke-26A5E4?logo=telegram)](https://t.me/excelvpotoke)

</div>

---

<div align="center">

**MyBestCars** - Выбери свой идеальный автомобиль! 🚀

</div>
