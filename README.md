# 1. Перейдите в папку проекта
cd путь/к/lab_02

# 2. Инициализируйте Git
git init

# 3. Добавьте все файлы
git add .

# 4. Сделайте первый коммит
git commit -m "Initial commit"

# 5. Свяжите с удалённым репозиторием (замените URL)
git remote add origin https://github.com/ВАШ_ЛОГИН/lab_02.git

# 6. Отправьте код на GitHub
git push -u origin main

# 7. Добавьте .gitignore и обновите репозиторий
git add .gitignore
git commit -m "chore: add .gitignore"
git push
