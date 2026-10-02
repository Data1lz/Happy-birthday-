# 🧗 Climb to Production

Іменинна гра для бекенд-розробника: лізь по канату, відповідай на питання, отримуй сюрприз 🎂

## Запуск локально

Просто відкрий `index.html` у браузері. Жодних залежностей.

## Як опублікувати на GitHub Pages

1. Створи новий репозиторій на GitHub, наприклад `birthday-rope` (Public).
2. Завантаж `index.html` і `README.md` (кнопка **Add file → Upload files**) або через git:
   ```bash
   git init
   git add .
   git commit -m "birthday rope"
   git branch -M main
   git remote add origin https://github.com/ТВІЙ_НІК/birthday-rope.git
   git push -u origin main
   ```
3. Відкрий **Settings → Pages**. У розділі *Build and deployment* обери **Deploy from a branch**, гілку `main`, папку `/ (root)` і натисни **Save**.
4. Через 1–2 хвилини сайт буде тут:
   `https://ТВІЙ_НІК.github.io/birthday-rope/`

## Персоналізація

- За замовчуванням ім'я: **Саня**. Змінити можна в рядку `var NAME` у `index.html`
  або прямо в посиланні: `...github.io/birthday-rope/?name=Вася`
- Питання лежать у масиві `Q`. Додавай свої, наприклад про його стек.
- Пасхалка: клікни 5 разів на 🎂 на вершині канату 😉
- Особисте побажання в кінці: змінні `MSG` і `FROM` на початку скрипта в `index.html`.
- Фінал: термінал → торт зі свічками (можна задувати **мікрофоном** — працює на https, тобто на GitHub Pages; або тапами) → феєрверк, що складається в слова.
