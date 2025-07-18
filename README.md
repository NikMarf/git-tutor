```

(Если Git не установлен, скачайте его с https://git-scm.com)

---

### 🛠️ Шаг 2: Настройка Git

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "ваш@email.com"
git config --list
```

---

### 📁 Шаг 3: Создание локального репозитория

```bash
cd путь/к/проекту
git init
git add .
git commit -m "Первый коммит"
```

---

### ☁️ Шаг 4: Создание удалённого репозитория на GitHub

1. Перейдите на https://github.com и нажмите **New repository**
2. Создайте новый пустой репозиторий (не добавляйте README, .gitignore и т.д.)

---

### 🔗 Шаг 5: Связывание локального репозитория с GitHub

```bash
git remote add origin https://github.com/ваш-юзернейм/имя-репозитория.git
git push -u origin master  # или main, если ваша ветка называется main
```

---

### 🔄 Полезные команды Git

```bash
git remote -v                      # Просмотр подключённых удалённых репозиториев
git clone https://github.com/юзер/репозиторий.git   # Клонирование репозитория
git pull origin main              # Получение изменений с удалённого репозитория
git push origin main              # Отправка изменений
```

---

### ✅ Заключение

Теперь вы умеете:

- Устанавливать и настраивать Git
- Инициализировать локальные репозитории
- Создавать удалённые репозитории на GitHub
- Связывать и синхронизировать их

---