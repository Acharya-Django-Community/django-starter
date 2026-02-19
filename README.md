Bu Repository Django Starter Project sifatida ishlatish uchun

Lokalda sozlash uchun 

ushbu repoyitoriyani clone qilish kerak 

```bash
git clone https://github.com/Acharya-Django-Community/django-starter.git
```
clone qilingandan song esa 

```bash
cd django-starter
```
keyingi qadam esa 

```bash
python -m venv venv # Bu Windowsda
```
```bash
python3 -m venv venv # Bu Linuxda
```

Activate venv

```bash
source venv/bin/activate #Linuxda
```

```bash
venv\Scripts\activate #Windowsda`

```
Keyingi qadam esa 

Kerakli kutubxonalarni ornatish boladi


```bash
pip install -r requirements.txt
```

```bash
python -c 'from  django.core.management.utils import get_random_secret_key;print(get_random_secret_key());'

```
chiqarilgan secret keyni biz .env filega yozishimiz kerak

Python serverni ishga tushiramiz

```bash
python manage.py runserver
```

Barovserda kiramiz http://127.0.0.1:8000/

Agar hammasi togri bolsa sizda Django Page ochiladi

Quyidagi rasmda ko'rsatilgan natija bo'lsa sizda hammasi togri bajarilgan boladi 

![](https://github.com/Acharya-Django-Community/django-starter/blob/main/img.png)