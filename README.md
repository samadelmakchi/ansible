# DevOps
دواپس یک فرهنگ و مجموعه‌ای از روش‌ها است که برای بهبود همکاری و ارتباط بین تیم‌های توسعه‌دهندگان (Development) و تیم‌های عملیات (Operations) طراحی شده است. هدف اصلی دواپس تسریع در فرآیند توسعه نرم‌افزار و کاهش فاصله بین نوشتن کد و پیاده‌سازی آن در محیط تولید است. این فرهنگ با استفاده از ابزارها و خودکارسازی فرآیندها، به تیم‌ها این امکان را می‌دهد که به‌طور مداوم نرم‌افزارها را تست، به‌روزرسانی، و مستقر کنند. دواپس بر اصول همکاری، بازخورد مداوم، و تحویل مداوم (CI/CD) تأکید دارد و به تیم‌ها کمک می‌کند تا نرم‌افزار را سریع‌تر و با کیفیت بالاتر ارائه دهند. 

[📜 آشنایی بیشتر با دواپس](./README-MORE.md)  
[🛠️ آشنایی با ابزارهای دواپس](./README-TOOLS.md)  
[✳️ راهنماهای مورد نیاز برای مهندسین دواپس](./README-CHEATSHEET.md)  
[🔅 راه اندازی و ست کردن شکن به صورت دستی](./README-SHEKAN.md)


---

### 🤖 نصب و کانفیگ سرور

نصب آنسیبل
```bash
# حذف نسخه‌های قدیمی Ansible (در صورت نیاز)
sudo apt remove ansible -y

# نصب Ansible از طریق apt
sudo apt update
sudo apt install ansible -y

# نصب Ansible (پیشنهاد شده)
sudo pip3 install ansible -y

# نصب ansible-lint
sudo apt install ansible-lint -y

# نصب مجموعه‌های مورد نیاز
sudo ansible-galaxy collection install community.docker

#  بررسی نسخه‌های نصب شده
ansible --version
ansible-lint --version
```

اجرای پلی بوک آنسیبل و کانفیگ سرور
```bash
sudo ansible-playbook playbook-server.yml
```

اجرای پلی بوک آنسیبل و نصب سرویس ها برای مشتریان
```bash
sudo ansible-playbook -i inventory_file.yml playbook.yml
```

---

### 🦊 ساخت Token برای اتصال به GitLab
جهت دریافت توکت در گیت لب به مسیر زیر بروید
```
GitLab >> Preferences >> Access tokens >> Add new token
```
و توکن بدست امده را در فایل inventory_file.yml و در متغیر gitlab_token بنویسید

---

### سرویس های مشتریان
📜 Gateway (8001 - ...)
```
```
📜 Portal Backend (3001 - ...)
```
```
📜 Portal Frontend (4001 - ...)
```
```

---

### ابزارهای نصب شده

🚦 Traefik
```
```

🐳 Portainer
```
```

⚙️ Webmin & Bind9
```
```

🐳 Dozzle
```
```

🐳 Uptime Kuma
```
```

📀 phpMyAdmin
```
```

📑 Log Management (Elasticsearch - Kibana - Fluentd - Logstash - Beats)
```
http://kibana:5601/
```

♻️ Jenkins
```
```

♻️ Harbor
```
```

♻️ SonarQube
```
```

♻️ Selenium
```
```

🖥️ Prometheus
```
```

🖥️ Zabbix
```
```

🖥️ Grafana
```
```

🖥️ Splunk
```
```
