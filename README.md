# Персональний помічник – Friendly Handbook

## Опис

Персональний помічник - це корисна програма з інтерфейсом командного рядка, яка містить контактну книгу, нотатки, калькулятор та може аналізувати папки.
Friendly Handbook вміє:

- зберігати контакти з номером телефону, ім’ям, електронною поштою, датою народження до своєї Книги контактів;
- змінювати та видаляти контакти;
- знаходити контакти за іменами;
- створювати нотатки та працювати з ними (пошук, редагування, видалення, сортування);
- додавати нотатки з тегами;
- сортувати файли у зазначеній папці за категоріями (зображення, документи, відео та ін.).

## Встановлення

Щоб встановити програму потрібно зайти у теку де знаходиться установчий пакет та у командному рядку ввести **pip install** або **pip install -e**.
Щоб перевірити наявність: команда **pip list**

## Запуск персонального помічника

В командному рядку необхідно ввести команду assistant_bot

## Інструкція для користувача

Відкрийте Персональний помічник та виберіть категорію:

- Книга контактів (AdressBook)
- Нотатки (NoteBook)
- Сортувач папок (SortFolder)
- Калькулятор (Calculator)

  ### AdressBook

  Команди для Книги контактів:
  | Команди | Аргументи | Результат |
  |---------|:---------:|-----------|
  | help | - | Показати список усіх команд |
  | hello | - | Почати роботу з помічником |
  | add contact | name | Додати новий контакт до Книги контактів |
  | add phone | name, phone | Додати номер телефону до існуючого контакту |
  | add email | name, email | Додати електронну пошту до існуючого контакту |
  | add birthday | name, birthday | Додати чи змінити день народження до існуючого контакту |
  | change phone | name, new phone | Змінити номер телефону вказаного контакту |
  | change email | name, new email | Змінити електронну пошту вказаного контакту |
  | change birthday | name, old birthday, new birthday | Змінити день народження вказаного контакту |
  | delete contact | name | Видалити контакт за вказаним ім’ям з Книги контактів |
  | delete phone | name, phone | Видалити номер телефону контакту з Книги контактів |
  | delete email | name, email | Видалити електронну пошту контакту з Книги контактів |
  | delete birthday | name, birthday | Видалити день народження контакту з Книги контактів |
  | get birthday | days | Показати в кого день народження через введену кількість днів |
  | show all | - | Показати всі контакти з Книги контактів |
  | find name | name | Знайти контакт |
  | exit, close, goodbye | - | Закінчити роботу або повернутися в головне меню |

  ### NoteBook

  Команди для нотатків:
  | Команда | Результат |
  |---------|-----------|
  | help | Показати список всих команд |
  | add note | Створити новий нотаток та зберегти в папку «Нотатки» |
  | delete note | Видалити нотатку |
  | find by tag | Пошук за тегами |
  | find note | Знайти нотатку за назвою |
  | show all notes | Вивести всі нотатки |
  | add tag | Додати тег до нотатки |
  | change tag | Змінити тег існуючого нотатку |
  | change text | Змінити текст існуючого нотатку |
  | change note | Редагувати нотатку |
  | close | Закінчити роботу з Нотатками |

  ### SortFolder

  Сортувач папок дозволяє сортувати файли за такими категоріями:

- зображення: [".jpeg", ".png", ".jpg", ".svg"],
- документи: [".doc", ".docx", ".txt", ".pdf", ".xlsx", ".pptx",],
- аудіо: [".mp3", ".ogg", ".wav", ".amr"],
- відео: [".avi", ".mp4", ".mov", ".mkv"],
- архіви: [".zip", ".gz", ".tar", “.rar”,]
- програмування: [".php", ".js", ".py", ".html", ".css"]
  Під час сортування скрипт розпаковує всі архіви, а потім поміщає їх разом з іншими файлами в нові папки - зображення, документи, аудіо, відео, архіви, програмування та інше.

Введіть шлях до папки для запуску сценарію, наприклад: C:\Users\user\Desktop\trash

### Calculator

Простий калькулятор вміє виконувати основні матиматичні дії.

## Наша команда - JustPython

- Team Lead: Олександр Юха
- Scrum Master: Олександр Куспис
- Python Developers: Іван Марковський, Олександр Кострицький, Олександр Коваленко
