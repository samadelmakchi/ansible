## IaC (Infrastructure as Code)
IaC (Infrastructure as Code) به مفهومی اشاره دارد که زیرساخت‌های سیستم‌ها، شبکه‌ها، سرورها و سایر منابع فناوری اطلاعات به صورت کد مدیریت و پیکربندی می‌شوند. در این روش، به جای انجام دستی تنظیمات یا نصب و پیکربندی اجزا، همه این فرآیندها با استفاده از کدهای قابل اجرایی مانند اسکریپت‌ها یا فایل‌های پیکربندی انجام می‌شود. این رویکرد به کاهش خطاهای انسانی، افزایش تکرارپذیری و انعطاف‌پذیری در محیط‌های تولید کمک می‌کند و همچنین امکان اتوماسیون کامل فرآیندهای پیکربندی و مدیریت زیرساخت را فراهم می‌کند.

### Ansible
Ansible یکی از ابزارهای محبوب برای پیاده‌سازی IaC است که برای اتوماسیون و مدیریت پیکربندی سیستم‌ها و سرورها استفاده می‌شود. این ابزار به‌وسیله‌ی زبان YAML (که به سادگی قابل فهم است) برای تعریف دستورالعمل‌ها و سناریوهای پیکربندی به کار می‌رود و به دلیل سادگی در استفاده و قابلیت مقیاس‌پذیری بالا محبوب است. Ansible بدون نیاز به نصب نرم‌افزار خاص روی سرورهای هدف، از طریق SSH به سیستم‌ها متصل می‌شود و عملیات مورد نظر را انجام می‌دهد، این ویژگی باعث می‌شود که آن را برای پروژه‌های کوچک تا بزرگ مناسب و قابل انعطاف کند.

---

### 🤖 نصب آنسیبل
جهت نصب Ansible دستورات زیر را اجرا کنید.

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:ansible/ansible
sudo apt update

sudo apt install ansible -y
sudo apt install ansible-lint -y

ansible --version
ansible-lint --version
```

### 🐳 نصب داکر
برای نصب Docker با استفاده از پکیج‌ها، فایل [install_docker.sh](./install_docker.sh) را اجرا کنید.

---

### 🕒 نصب کرون
برای بررسی و نصب کرون در صورت عدم وجود، از دستور زیر استفاده کنید:

```bash
sudo apt-get install -y cron || sudo apt-get install cron
```

---

### 🚦 نصب Traefik
برای نصب Traefik در صورت نیاز از دستور زیر استفاده کنید
```bash
cd traefik

docker-compose up -d

docker network create traefik_reverse_proxy
```

---

### 🦊 ساخت Token برای اتصال به GitLab
جهت دریافت توکت در گیت لب به مسیر زیر بروید
```
GitLab >> Preferences >> Access tokens >> Add new token
```
و توکن بدست امده را در فایل inventory_file.yml و در متغیر gitlab_token بنویسید

---

### 🚀 اجرای پلی بوک آنسیبل
```bash
sudo ansible-playbook -i inventory_file.yml playbook.yml
```
---

### 📚 راهنمای جامع آنسیبل
برای آشنایی بیشتر با دستورات انسیبل، فایل [Ansible Cheat Sheet](./ansible_cheat_sheet.md) را مطالعه کنید.

