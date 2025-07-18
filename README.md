## Гайд по работе с Git и разворачиванием удаленного репозитория на GitHub

В этом гайде я попробую описать основные действия по созданию локального Git репозитория, а также поймем как связывать свой локальный Git репозиторий с его удаленной версией размещенной на платформе GitHub.

---

### 📦 Шаг 1: Установка Git

Перед началом убедитесь, что Git установлен на вашем компьютере. Для установки на *Windows* можете воспользоваться следующей ссылкой: [кликни сюда.](https://www.yandex.ruhttps://github.com/git-for-windows/git/releases/download/v2.50.1.windows.1/Git-2.50.1-64-bit.exe)

#### Проверка установки:
```bash
git --version
```
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
git add --all
git commit -m "Первый коммит"
```
---

### ☁️ Шаг 4: Создание удалённого репозитория на GitHub

1. Перейдите на https://github.com и нажмите **New repository**
2. Создайте новый пустой репозиторий

---

### 🔗 Шаг 5: Связывание локального репозитория с GitHub

```bash
git remote add origin https://github.com/ваш-юзернейм/имя-репозитория.git
git push -u origin master  # или main, если ваша ветка называется main
```

---

### 🔄 Полезные команды Git

```bash
git remote -v    # Просмотр подключённых удалённых репозиториев
git clone https://github.com/юзер/репозиторий.git    # Клонирование репозитория
git status    # Проверка состояния локального репозитория
```

---

### ✅ Заключение

Теперь вы умеете:

- Устанавливать и настраивать Git
- Инициализировать локальные репозитории
- Создавать удалённые репозитории на GitHub
- Связывать и синхронизировать их

---