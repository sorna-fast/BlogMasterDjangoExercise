# BlogMasterDjangoExercise

**English** | [فارسی](#فارسی)

## Introduction
This project is a simple yet powerful blog built using the Django framework. The goal is to provide a platform for creating, editing, and displaying articles using Django best practices. This README includes complete steps for installation, setup, usage, testing, and development.

## Prerequisites
Ensure your system has:
- **Python 3.6** or higher
- **pip** (Python package manager)
- (Optional) **virtualenv** for isolated environments

## Installation & Setup

### 1. Clone the Repository
Clone the source code from GitHub:
```bash
git clone https://github.com/YourUsername/YourProjectName.git
cd YourProjectName
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
```
Activate the virtual environment:
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **Linux/Mac:**
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies
Install packages from `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
Set up the database:
```bash
python manage.py migrate
```

### 5. Create a Superuser (Optional)
```bash
python manage.py createsuperuser
```
Follow the prompts to set up a username, email, and password.

### 6. Run the Development Server
```bash
python manage.py runserver
```
Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Project Structure
```
- mysite/            # Main project folder
  - settings.py      # Project settings
  - urls.py          # Main URL configurations
- blog/              # Blog app
  - admin.py         # Admin panel registration
  - models.py        # Database models (articles, categories)
  - templates/       # HTML templates
  - static/          # CSS, JS, images
  - migrations/      # Database migration files
- db.sqlite3         # Default SQLite database (development)
- manage.py          # Django management tool
```

## Usage

### View the Blog
Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to see the blog.

### Access the Admin Panel
1. Go to [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).
2. Log in with your superuser credentials.

### Create/Edit Articles
- Use the admin panel to manage articles.
- Public pages display articles and their details.

## Development Notes

### Model Changes
After modifying models:
```bash
python manage.py makemigrations
python manage.py migrate
```

### Static Files (Production)
```bash
python manage.py collectstatic
```

### Environment Settings
Modify `mysite/settings.py` for database, email, etc.

## License
MIT License

## Contact
- Created with ❤️ by [Sorna](https://github.com/sorna-fast)
- Email: masudpythongit@gmail.com

---

# فارسی

## مقدمه
این پروژه یک وبلاگ ساده و قدرتمند با استفاده از فریمورک Django است. هدف، ایجاد بستری برای تولید، ویرایش و نمایش مقالات با روش‌های بهینه جنگو می‌باشد. این فایل شامل مراحل نصب، راه‌اندازی، استفاده، تست و توسعه پروژه است.

## پیش‌نیازها
- **پایتون 3.6** یا بالاتر
- **pip** (مدیر بسته‌های پایتون)
- (اختیاری) **virtualenv** برای محیط‌های مجزا

## نصب و راه‌اندازی

### 1. کلون کردن مخزن
```bash
git clone https://github.com/YourUsername/YourProjectName.git
cd YourProjectName
```

### 2. ایجاد محیط مجازی (اختیاری)
```bash
python -m venv venv
```
فعالسازی محیط:
- **ویندوز:**
  ```bash
  venv\Scripts\activate
  ```
- **لینوکس/مک:**
  ```bash
  source venv/bin/activate
  ```

### 3. نصب بسته‌ها
```bash
pip install -r requirements.txt
```

### 4. اعمال مهاجرت‌ها
```bash
python manage.py migrate
```

### 5. ایجاد سوپر کاربر (اختیاری)
```bash
python manage.py createsuperuser
```

### 6. اجرای سرور توسعه
```bash
python manage.py runserver
```
به آدرس [http://127.0.0.1:8000](http://127.0.0.1:8000) مراجعه کنید.

## ساختار پروژه
```
- mysite/            # پوشه اصلی پروژه
  - settings.py      # تنظیمات پروژه
  - urls.py          # تنظیمات URL اصلی
- blog/              # اپلیکیشن وبلاگ
  - admin.py         # ثبت مدل‌ها در پنل مدیریت
  - models.py        # مدل‌های پایگاه داده (مقالات، دسته‌بندی‌ها)
  - templates/       # قالب‌های HTML
  - static/          # فایل‌های استاتیک
  - migrations/      # فایل‌های مهاجرت
- db.sqlite3         # پایگاه داده پیش‌فرش SQLite
- manage.py          # ابزار مدیریت جنگو
```

## نحوه استفاده

### مشاهده وبلاگ
به آدرس [http://127.0.0.1:8000](http://127.0.0.1:8000) بروید.

### پنل مدیریت
1. آدرس [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).
2. با حساب سوپر کاربر وارد شوید.

### مدیریت مقالات
- از پنل مدیریت برای ایجاد یا ویرایش مقالات استفاده کنید.
- صفحات عمومی، مقالات را نمایش می‌دهند.

## نکات توسعه

### تغییر مدل‌ها
پس از تغییر مدل‌ها:
```bash
python manage.py makemigrations
python manage.py migrate
```

### فایل‌های استاتیک (محیط تولید)
```bash
python manage.py collectstatic
```

### تنظیمات محیطی
ویرایش `mysite/settings.py` برای پایگاه داده، ایمیل و غیره.

## مجوز
مجوز MIT

## ارتباط با توسعه‌دهنده
- ساخته شده با ❤️ توسط [Sorna](https://github.com/sorna-fast)
- ایمیل: masudpythongit@gmail.com