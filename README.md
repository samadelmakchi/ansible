# DevOps
دواپس یک فرهنگ و مجموعه‌ای از روش‌ها است که برای بهبود همکاری و ارتباط بین تیم‌های توسعه‌دهندگان (Development) و تیم‌های عملیات (Operations) طراحی شده است. هدف اصلی دواپس تسریع در فرآیند توسعه نرم‌افزار و کاهش فاصله بین نوشتن کد و پیاده‌سازی آن در محیط تولید است. این فرهنگ با استفاده از ابزارها و خودکارسازی فرآیندها، به تیم‌ها این امکان را می‌دهد که به‌طور مداوم نرم‌افزارها را تست، به‌روزرسانی، و مستقر کنند. دواپس بر اصول همکاری، بازخورد مداوم، و تحویل مداوم (CI/CD) تأکید دارد و به تیم‌ها کمک می‌کند تا نرم‌افزار را سریع‌تر و با کیفیت بالاتر ارائه دهند. 

[✳️ راهنماهای مورد نیاز برای مهندسین دواپس](cheatsheet/README.md)  

---

### 🤖 نصب و کانفیگ سرور

نصب آنسیبل
```bash
# Remove old versions of Ansible (if needed)
sudo apt remove ansible -y

# Install Ansible via apt
sudo apt update
sudo apt install ansible -y

# Install Ansible (recommended)
sudo pip3 install ansible -y

# Install ansible-lint
sudo apt install ansible-lint -y

# Install the required packages
sudo ansible-galaxy collection install community.docker

# Check installed versions
ansible --version
ansible-lint --version
```

اجرای پلی بوک آنسیبل و کانفیگ سرور
```bash
sudo ansible-playbook -i inventory-server.yml playbook-server.yml
```

اجرای پلی بوک آنسیبل و نصب سرویس ها برای مشتریان
```bash
sudo ansible-playbook -i inventory.yml playbook.yml
```

---

### 🦊 ساخت Token برای اتصال به GitLab
جهت دریافت توکن در گیت لب به مسیر زیر بروید
```
GitLab >> Preferences >> Access tokens >> Add new token
```
و توکن بدست امده را در فایل inventory.yml و در متغیر gitlab_token بنویسید

---

### سرویس های مشتریان
📜 Gateway (10101 - ...)

📜 Portal Backend (10201 - ...)

📜 Portal Frontend (10301 - ...)

---

### ابزارهای نصب شده

Server
- ⚙️ Traefik (80) (user: admin - pass: admin)
- ⚙️ Portainer (9000)
- ⚙️ Bind9 (-)
- ⚙️ Mailu (?)
- ⚙️ Rancher (?)

Develop
- ✳️ Apprise (8073)
- ✳️ Nginx (?)
- ✳️ RabbitMQ (15672)
- ✳️ Ceph (?)

Tools
- 🛠️ phpMyAdmin (8083)

Logs Management
- 📑 Elasticsearch (-)
- 📑 Logstash (-)
- 📑 Beats (-)
- 📑 Fluentd (?)
- 📑 Kibana (5601)
- 📑 Dozzle (8080)

CICD
- ♻️ Gitlab (?)
- ♻️ Jenkins (8081)
- ♻️ Nexus (8084)
- ♻️ SonarQube (9001)
- ♻️ Selenium (4444 - Chrome: 5900 - Firefox: 5901)

Monitoring
- 🖥️ Prometheus (9090)
- 🖥️ Zabbix (8082)
- 🖥️ Grafana (3000)
- 🖥️ Splunk (8000)
- 🖥️ Uptime Kuma (3001)
