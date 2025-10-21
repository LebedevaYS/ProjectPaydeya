
# Paydeya Frontend

Фронтенд приложение для проекта Paydeya, построенное на React + Vite.

## 📋 Что нужно установить перед началом

### 1. Установите Git
- **Windows**: Скачайте с [git-scm.com](https://git-scm.com/) → Установите как обычную программу
- **Mac**: Откройте Terminal → Введите `git` → Следуйте инструкциям
- **Linux**: Откройте Terminal → Введите `sudo apt install git`

### 2. Установите Node.js
- Скачайте LTS версию с [nodejs.org](https://nodejs.org/)
- Установите как обычную программу
- **Проверьте установку**: Откройте Terminal → Введите `node --version` → Должна появиться версия Node.js

### 3. Установите редактор кода
- **VS Code** 
- **Intelliji IDEA**
- Или любой другой редактор

## 🚀 Быстрый старт

### Локальная разработка

```bash
# Клонирование репозитория
git clone https://github.com/LebedevaYS/ProjectPaydeya-frontend.git
cd ProjectPaydeya-frontend

# Установка зависимостей
npm install

# Запуск dev сервера
npm run dev
```

Приложение будет доступно по адресу: http://localhost:5173

## 🔧 Git команды (рабочий процесс)

### 🆕 Начало работы над новой фичей

```bash
# Обновить основную ветку
git checkout main
git pull origin main

# Создать новую ветку для фичи
git checkout -b feature/название-фичи
```

### 💾 Ежедневный workflow

```bash
# Проверить статус изменений
git status

# Добавить изменения
git add .

# Создать коммит с понятным сообщением
git commit -m "добавлен новый компонент"

# Отправить изменения
git push origin feature/название-фичи
```

### 🧹 Поддержание чистоты истории

```bash
# Просмотр изменений перед коммитом
git diff

# Отмена непроиндексированных изменений
git restore .

# Отмена последнего коммита (осторожно!)
git reset --soft HEAD~1
```