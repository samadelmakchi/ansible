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
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:ansible/ansible
sudo apt update

sudo apt install ansible -y
sudo apt install ansible-lint -y

ansible --version
ansible-lint --version
```

اجرای پلی بوک آنسیبل و کانفیگ سرور
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

<!-- 
نصب ابزارهای کانتینر و مجازی سازی
sudo chmod +x ./tools/install_docker.sh 

نصب ابزارهای مدیریت لاگ ها
sudo docker compose -f tools/logs/docker-compose.yml up -d


🖥️ Prometheus Zabbix Grafana Splunk

♻️ Jenkins Harbor SonarQube Selenium

Kubernetes
Portainer
Rancher
kind(+++) / k0s(+++) / k3s(++) / Minikube(+)
-->