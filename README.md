# BizMath

> Калькулятор амортизации и ликвидности для малого бизнеса

![Версия](https://img.shields.io/badge/version-1.0.0-blue)
![Nuxt](https://img.shields.io/badge/Nuxt.js-3.x-brightgreen)
![Лицензия](https://img.shields.io/badge/license-MIT-lightgrey)

## О проекте

BizMath автоматизирует расчёты трёх методов амортизации (линейный, уменьшаемого остатка, сумма чисел лет) и трёх коэффициентов ликвидности (текущий, быстрый, абсолютный). Создан для малых предприятий и бухгалтеров, которым нужны быстрые и точные расчёты без Excel и 1С.

**Демо:** [ссылка, если задеплоили]

## Основные функции

- 📊 Расчёт амортизации с таблицей и графиком
- 📈 Три коэффициента ликвидности с цветовой индикацией нормы
- 💾 Сохранение, редактирование и удаление активов в базе данных
- 📱 Адаптивный дизайн (Bootstrap 5)

## Технологии

- **Frontend:** Nuxt.js (Vue 3), Bootstrap 5, Chart.js, dayjs, axios
- **Backend:** Nuxt server routes, MongoDB + Mongoose
- **Деплой:** Vercel + MongoDB Atlas

## Быстрый старт

```bash
# Клонировать репозиторий
git clone https://github.com/ваш-аккаунт/bizmath.git
cd bizmath

# Установить зависимости
npm install

# Создать файл .env и добавить MONGODB_URI
echo "MONGODB_URI=mongodb+srv://..." > .env

# Запустить в режиме разработки
npm run dev
>>>>>>> a7cea863658221403a7e0de04991f84c6e8fccf1
