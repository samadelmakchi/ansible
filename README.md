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
📜 Gateway (10101 - ...)
```
```
📜 Portal Backend (10201 - ...)
```
```
📜 Portal Frontend (10301 - ...)
```
```

---

### ابزارهای نصب شده

🚦 Traefik (80)
```
http://traefik:80/
```

🐳 Portainer (9000)
```
http://portainer:9000/
```

⚙️ Webmin & Bind9 (10000)
```

```

🐳 Dozzle (8080)
```
http://dozzle:8080/
```

🐳 Uptime Kuma (3001)
```
http://uptime-kuma:3001/
```

📀 phpMyAdmin (8083)
```
http://phpmyadmin:8083/
```

📑 Log Management (Elasticsearch - Kibana - Fluentd - Logstash - Beats) (5601)
```
http://kibana:5601/
```

♻️ Jenkins (8081)
```

```

♻️ Harbor (9010)
```

```

♻️ SonarQube (9001)
```
http://sonarqube:9001/
```

♻️ Selenium (4444 - Chrome: 5900 - Firefox: 5901)
```

```

🖥️ Prometheus (9090)
```

```

🖥️ Zabbix (8082)
```

```

🖥️ Grafana (3000)
```

```

🖥️ Splunk (8000)
```

```
