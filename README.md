# П.Р.О.М.О.

Цей сервіс допоможе користувачам швидко знаходити, порівнювати та отримувати актуальні акційні пропозиції у їхньому місті.
Платформа збирає інформацію про знижки, спеціальні умови та промо-акції від магазинів, супермаркетів та інших закладів, надаючи користувачам доступ до найвигідніших пропозицій.

---

## Головні особливості

### **Пошук акцій та знижок**
- Дозволить користувачам швидко знаходити актуальні акційні пропозиції саме на ті товари, які їх цікавлять.

### **Порівняння товарів**
- Допоможе аналізувати, де обраний товар є найвигіднішим за ціною, якістю або умовами акції, економлячи час на ручне порівняння пропозицій.

### **Відображення акцій на мапі**
- Забезпечить зручний спосіб перегляду акцій, поєднуючи мапу міста та фільтри для зручності пошуку.

### **Додавання та оновлення акцій**
- Дозволить користувачам з розширеними можливостями самостійно додавати та оновлювати інформацію про акційні пропозиції.

---

## Технічна інформація

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python
- **Framework:** Django
- **Database:** PostgreSQL

---

## Налаштування проекту

### **Синхронізація проекту**
```bash
git pull
```
Оновіть локальну версію проекту, щоб отримати останні зміни.

### **Створення віртуального оточення**
```bash
python -m venv venv
```

### **Активація віртуального оточення**
- Windows:
```bash
venv\Scripts\activate
```
- Linux/Mac:
```bash
source venv/bin/activate
```

### **Встановлення залежностей**
```bash
pip install -r requirements.txt
```

### **Налаштування змінних оточення**
```bash
cp .env.example .env
```
Скопіюйте файл .env.example як .env та впишіть в нього дані для підключення до бази даних.

### **Застосування міграцій**
```bash
python manage.py migrate
```

### **Запуск серверу розробки**
```bash
python manage.py runserver
```
