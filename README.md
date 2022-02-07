
## ТЗ:
### Вступ
#### 1. Ціль:
* написати веб-сайт (інтернет-магазин, де можна купувати відеоігри).
#### 2. Короткий опис:
* На веб-сайті має бути наявна можливість шукати та купувати ігри, залишати оцінки, відгуки.
* При пошуку є можливість використовувати фільтри та сортування, а також знаходити за назвою.
### Опис функціоналу:
#### 1. Користувачі:
* **Неавторизовані користувачі можуть:**
    1. Переглядати товари
    2. Шукати товари
    3. Купувати товари
*  **Авторизовані користувачі можуть:**
    1. Переглядати товари
    2. Шукати товари
    3. Купувати товари
    4. Залишати оцінки, відгуки
    5. Бачити історію придбань (на сторінці «Мій профіль»)
    
*   **Адміністратори можуть:**
    1. Переглядати товари;
    2. Шукати товари;
    3. Додавати товари, редагувати вміст;
    4. Бачити список користувачів;
    5. Залишати відгуки.

#### 2. Фільтри для товарів:
    • За ціною (вводити мінімальне та максимальне значення)
    • За платформою (PC(Windows,Linux,MacOS), Playstation, XBOX)
    • За категоріями
    • За віковим рейтингом
    • За рейтингом від користувачів

#### 3. Сортування товарів:
    • За ціною;
    • За рейтингом користувачів;
    • За датою виходу.

#### 4. Пошукова стрічка:
    * Пошукова дозволяє користувачу знайти гру з назвою

#### 5. Авторизація та регістріція:
     • Авторизація за електронною поштою та паролем
     • Регістрація:
        1. Обов'язкове поле:  електронна пошта,пароль, прізвище та ім’я
        2. Необов'язкове: дата народження, місто проживання, номер телефону

#### 6. Характеристики товару:
    • Назва;
    • Короткий опис;
    • Фото;
    • Ціна;
    • Дата виходу;
    • Категорія;
    • Платформа;
    • Віковий рейтинг;
    • Видавник;
    • Наявний/не наявний.
    • Системні вимоги (необов’язково).

### Опис головних елементів інтерфейсу
#### Вигляд головної сторінки
    1. Верхня панель: 
        пошукова стрічка, кнопка авторизації та виходу, опція «Мій профіль» у разі якщо користувач авторизований
    2. Бокова ліва панель:
        список сортувань та фільтрів.
    3. Основна панель:
        список ігор (спочатку показувати ігри, відсортовані по рейтингу користувачів).
    4. Нижня панель 
        список контактів, інформація про розробників.

#### Вигляд сторінки обраного товару
    1. Верхня панель
        зберігається з вигляду головної сторінки,  додається опція «Назад».
    2.  Основна панель 
        Інформація про гру, опція «Купити», поле для коментаря, список коментарів.
    3. Нижня панель 
        зберігається з вигляду головної сторінки.
