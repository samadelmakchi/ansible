# DevOps
DevOps یک فرهنگ و مجموعه‌ای از روش‌ها است که برای بهبود همکاری و ارتباط بین تیم‌های توسعه‌دهندگان (Development) و تیم‌های عملیات (Operations) طراحی شده است. هدف اصلی DevOps تسریع در فرآیند توسعه نرم‌افزار و کاهش فاصله بین نوشتن کد و پیاده‌سازی آن در محیط تولید است. این فرهنگ با استفاده از ابزارها و خودکارسازی فرآیندها، به تیم‌ها این امکان را می‌دهد که به‌طور مداوم نرم‌افزارها را تست، به‌روزرسانی، و مستقر کنند. DevOps بر اصول همکاری، بازخورد مداوم، و تحویل مداوم (CI/CD) تأکید دارد و به تیم‌ها کمک می‌کند تا نرم‌افزار را سریع‌تر و با کیفیت بالاتر ارائه دهند.  

![DevOps](./img/devops.jpg)

<!-- SMD -->
<details>
  <summary>Collaboration & Culture (فرهنگ سازی و همکاری)</summary>
  <p>
    ▫️Trello
  </p>
</details>
<details>
  <summary>Planning & Tracking (برنامه ریزی و پیگیری)</summary>
  <p>
    ▫️Jira
    ▫️Scrum
    ▫️Agile
  </p>
</details>
<details>
  <summary>Build & Deployment (ساخت و توسعه)</summary>
  <p>
    ▫️Gitlab
    ▫️Github
    ▫️Docker
    ▫️Git (Git Flow)
    🔸RabbitMQ
    🔸Ceph
  </p>
</details>
<details>
  <summary>CI/CD (ادغام و تحویل پیوسته)</summary>
  <p>
    ▫️Jenkins
    ▫️Bash
    🔸Gitlab CI
    🔸Github Action
    🔸ArgoCD
  </p>
</details>
<details>
  <summary>Testing (تست)</summary>
  <p>
    ▫️Selenium
    ▫️SonarQube
    ▫️pyTest
    ▫️Postman
    🔸Appium
    🔸Cypress
  </p>
</details>
<details>
  <summary>Release & Deploy (انتشار و استقرار)</summary>
  <p>
    ▫️Ansible
    ▫️Docker Compose
    ▫️Traefik
    ▫️Terraform
    ▫️Nexus
    🔸HAProxy
    🔸Nginx
  </p>
</details>
<details>
  <summary>Oprate (عملیات)</summary>
  <p>
    ▫️Kubernetes
    ▫️Portainer
    ▫️Rancher
    ▫️kind(+++) / k0s(+++) / k3s(++) / Minikube(+)
  </p>
</details>
<details>
  <summary>Monitoring & Feedback (پایش و بازخورد)</summary>
  <p>
    ▫️Elasticsearch  
    ▫️Kibana
    ▫️Fluentd
    ▫️Beats(Filebeat, Metricbeat, Packetbeat, Heartbeat, Auditbeat)
    🔸Logstash
    🔸Dozzle

    ▫️Prometheus
    ▫️Zabbix
    ▫️Grafana
    🔸Splunk
    🔸Netdata
    🔸Uptime Kuma
  </p>
</details>

### 🤖 اصطلاحات
<details>
  <summary>IaC (Infrastructure as Code)</summary>
  <p>
    به مفهومی اشاره دارد که زیرساخت‌های سیستم‌ها، شبکه‌ها، سرورها و سایر منابع فناوری اطلاعات به صورت کد مدیریت و پیکربندی می‌شوند. در این روش، به جای انجام دستی تنظیمات یا نصب و پیکربندی اجزا، همه این فرآیندها با استفاده از کدهای قابل اجرایی مانند اسکریپت‌ها یا فایل‌های پیکربندی انجام می‌شود. این رویکرد به کاهش خطاهای انسانی، افزایش تکرارپذیری و انعطاف‌پذیری در محیط‌های تولید کمک می‌کند و همچنین امکان اتوماسیون کامل فرآیندهای پیکربندی و مدیریت زیرساخت را فراهم می‌کند.
  </p>
</details>
<details>
  <summary>Continuous Integration</summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>Continuous Delivery/Continuous Deployment</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

### 🤖 مهندس دواپس
<details>
  <summary>مهندس دواپس</summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>مهندسی قابلیت اطمینان سایت</summary>
  <p>
    Site Reliability Engineering (SRE) یک رشته مهندسی است که بر روی بهبود قابلیت اطمینان، عملکرد و مقیاس‌پذیری سیستم‌های نرم‌افزاری در مقیاس‌های بزرگ تمرکز دارد. این حوزه با ترکیب اصول مهندسی نرم‌افزار و عملیات، تلاش می‌کند تا سیستم‌های پیچیده را به‌طور مداوم قابل اعتماد، کارآمد و مقیاس‌پذیر نگه دارد. SRE به‌طور خاص بر روی بهبود دسترسی، کاهش زمان‌های خرابی، و مدیریت ترافیک در سیستم‌های توزیع‌شده تمرکز دارد و از شاخص‌های کلیدی مانند Service Level Objectives (SLO) و Service Level Indicators (SLI) برای ارزیابی و بهبود عملکرد سیستم‌ها استفاده می‌کند. علاوه بر این، SRE از خودکارسازی، نظارت دقیق، و فرآیندهای خطایابی برای جلوگیری از بروز مشکلات و کاهش زمان‌های خرابی استفاده می‌کند، به طوری که تیم‌های توسعه بتوانند بیشتر بر روی ویژگی‌های جدید و توسعه محصولات تمرکز کنند.
  </p>
</details>
<details>
  <summary>تفاوت مهندس دواپس با مهندسی قابلیت اطمینان سایت</summary>
  <p>
    تفاوت DevOps با SRE در این است که Site Reliability Engineering (SRE) بیشتر بر حفظ و بهبود قابلیت اطمینان سیستم‌های تولید تمرکز دارد. در حالی که DevOps به‌طور کلی به یکپارچه‌سازی توسعه و عملیات می‌پردازد و بر خودکارسازی، سرعت و بهره‌وری تاکید دارد، SRE با استفاده از اصول مهندسی نرم‌افزار و روش‌های دقیق‌تر، به‌ویژه در مورد نظارت و نگهداری سیستم‌های مقیاس‌پذیر، به تضمین عملکرد، در دسترس بودن و قابلیت اطمینان سیستم‌ها می‌پردازد. در واقع، SRE به‌عنوان یک تخصص در داخل DevOps دیده می‌شود که بیشتر بر روی عملکرد و پایداری سیستم‌های عملیاتی تمرکز دارد.
  </p>
</details>
<details>
  <summary>مهندس کلود</summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>تفاوت مهندس دواپس با مهندس کلود</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

---

### 🤖 Ansible
<details>
  <summary>Ansible</summary>
  <p>آنسیبل یکی از ابزارهای محبوب برای پیاده‌سازی زیرساخت به عنوان کد است که برای اتوماسیون و مدیریت پیکربندی سیستم‌ها و سرورها استفاده می‌شود. این ابزار به‌وسیله‌ی زبان YAML (که به سادگی قابل فهم است) برای تعریف دستورالعمل‌ها و سناریوهای پیکربندی به کار می‌رود و به دلیل سادگی در استفاده و قابلیت مقیاس‌پذیری بالا محبوب است. آنسیبل بدون نیاز به نصب نرم‌افزار خاص روی سرورهای هدف، از طریق SSH به سیستم‌ها متصل می‌شود و عملیات مورد نظر را انجام می‌دهد، این ویژگی باعث می‌شود که آن را برای پروژه‌های کوچک تا بزرگ مناسب و قابل انعطاف کند.  
جهت نصب آنسیبل دستورات زیر را اجرا کنید.</p>
</details>

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

جهت اجرای پلی بوک آنسیبل از دستور زیر استفاده بکنید.
```bash
sudo ansible-playbook -i inventory_file.yml playbook.yml
```

---

### 🐳 Docker
<details>
  <summary>Docker</summary>
  <p>
    داکر (Docker) یک پلتفرم کانتینرسازی سطح پایین و مبتنی بر فناوری‌های کرنل لینوکس مانند cgroups و namespaces است که امکان اجرای اپلیکیشن‌ها در محیطی ایزوله به‌نام کانتینر را فراهم می‌کند. برخلاف ماشین‌های مجازی، کانتینرها به‌طور مستقیم روی کرنل سیستم‌عامل میزبان اجرا می‌شوند و تنها شامل باینری‌ها و وابستگی‌های مورد نیاز اپلیکیشن هستند، که این موضوع باعث سبک‌تر بودن و مصرف منابع کمتر آن‌ها می‌شود. داکر از یک معماری کلاینت/سرور بهره می‌برد که در آن Docker Engine مسئول ساخت، اجرا و مدیریت کانتینرها است و Docker CLI یا API برای تعامل با آن استفاده می‌شود. همچنین با استفاده از Docker Compose می‌توان چند سرویس را به‌صورت تعریف‌شده در یک فایل YAML مدیریت کرد و با ترکیب آن با ابزارهایی مانند Kubernetes یا Swarm، امکان ارکستراسیون و مقیاس‌پذیری اپلیکیشن‌ها نیز فراهم می‌شود.
  </p>
</details>
<details>
  <summary>Docker Compose</summary>
  <p>
    Docker Compose یک ابزار متن‌باز است که به شما امکان می‌دهد چندین کانتینر Docker را به‌طور همزمان و به‌صورت هماهنگ مدیریت کنید. این ابزار با استفاده از یک فایل YAML به نام docker-compose.yml، تنظیمات کانتینرهای مختلف را تعریف کرده و آن‌ها را به‌طور خودکار راه‌اندازی می‌کند. Docker Compose برای پروژه‌های پیچیده که به چندین سرویس مختلف نیاز دارند، مانند یک اپلیکیشن وب که نیاز به پایگاه‌داده، کش، و سرویس‌های مختلف دارد، بسیار مفید است. به جای اجرای هر کانتینر به‌طور دستی، Docker Compose به شما این امکان را می‌دهد که تمام سرویس‌ها را با یک دستور ساده (docker-compose up) شروع، متوقف و مدیریت کنید. این ابزار به‌ویژه در فرآیند توسعه، تست و استقرار اپلیکیشن‌های مبتنی بر میکروسرویس‌ها یا چندین سرویس مختلف کاربرد دارد و فرایندهای خودکارسازی را تسهیل می‌کند.
  </p>
</details>
<details>
  <summary>Dockerize</summary>
  <p>
    Dockerize به فرآیند تبدیل یک اپلیکیشن یا سرویس به یک کانتینر Docker گفته می‌شود، به‌طوری که اپلیکیشن می‌تواند به‌راحتی در هر محیطی اجرا شود، بدون توجه به پیکربندی یا وابستگی‌های سیستم عامل میزبان. این فرآیند شامل ایجاد یک فایل Dockerfile است که تمامی مراحل مورد نیاز برای ساخت کانتینر، از جمله نصب وابستگی‌ها، پیکربندی محیط و کپی کردن کدهای اپلیکیشن به داخل کانتینر را تعریف می‌کند. با Dockerize کردن اپلیکیشن‌ها، توسعه‌دهندگان می‌توانند محیط‌های پایدار و قابل پیش‌بینی برای اجرا و تست ایجاد کنند و از مشکلات مرتبط با تفاوت‌های سیستم‌عاملی جلوگیری کنند. این فرآیند در پروژه‌های مختلف، به‌ویژه در پروژه‌های چندسرویس و میکروسرویس‌ها، بسیار مهم است زیرا باعث تسهیل در استقرار، مقیاس‌پذیری و حمل‌پذیری اپلیکیشن‌ها می‌شود.
  </p>
</details>

برای نصب Docker با استفاده از پکیج‌ها، فایل [install_docker.sh](./install_docker.sh) را اجرا کنید.

<!-- SMD
نصب برخی کامپزهای مهم
▫️Docker Compose
▫️Dozzle
▫️Portainer 
-->

---

### 🚦 Traefik
<details>
  <summary>Traefik</summary>
  <p>
    یک پروکسی معکوس (reverse proxy) و لود بالانسر مدرن و قدرتمند است که به‌طور ویژه برای محیط‌های داینامیک مانند Docker، Kubernetes، و سایر پلتفرم‌های ابری طراحی شده است. یکی از ویژگی‌های برجسته Traefik، توانایی کشف خودکار سرویس‌ها (Service Discovery) از طریق برقراری ارتباط با API پلتفرم‌های زیرساختی است؛ به این معنی که به محض اضافه یا حذف شدن یک سرویس، تنظیمات مربوط به روتینگ به‌صورت خودکار به‌روزرسانی می‌شود. Traefik از پروتکل‌های HTTP، HTTPS، TCP و حتی gRPC پشتیبانی می‌کند و به‌راحتی می‌تواند گواهی‌های TLS را به‌صورت خودکار از طریق Let’s Encrypt مدیریت کند. این ابزار به‌خاطر پیکربندی ساده، داشبورد گرافیکی کاربرپسند، و قابلیت ادغام با ابزارهایی مانند Docker Compose و Helm، در بین توسعه‌دهندگان و تیم‌های DevOps بسیار محبوب است.  
  </p>
</details>

برای نصب Traefik دستورات زیر را اجرا کنید.
```bash
cd traefik
sudo docker compose up -d

sudo docker network create traefik_reverse_proxy
```

---

### 📄 Elasticsearch, Kibana, Fluentd, Beats
<details>
  <summary>Elasticsearch (ذخیره و جستجو لاگ‌ها)  </summary>
  <p>
    در یک معماری مدرن برای جمع‌آوری، ذخیره و مانیتورینگ لاگ‌ها، ابزارهای مختلفی با نقش‌های مشخص استفاده می‌شوند. Elasticsearch یک موتور جستجوی توزیع‌شده و قدرتمند است که برای ذخیره‌سازی، ایندکس‌گذاری و جستجوی سریع در حجم بالایی از لاگ‌ها استفاده می‌شود. Kibana به‌عنوان رابط کاربری گرافیکی برای Elasticsearch، امکان نمایش، فیلتر، مصورسازی و مانیتورینگ لاگ‌ها و متریک‌ها را فراهم می‌کند. Fluentd یک جمع‌آور و پردازشگر لاگ انعطاف‌پذیر است که می‌تواند لاگ‌ها را از منابع مختلف دریافت، پردازش و به مقصدهایی مانند Elasticsearch ارسال کند. برخلاف Logstash که برای پردازش‌های پیچیده و سنگین‌تر مناسب است، Fluentd سبک‌تر و مناسب‌تر برای اغلب نیازهای جمع‌آوری لاگ است. در کنار آن‌ها، خانواده Beats (مانند Filebeat، Metricbeat، Packetbeat و ...) ابزارهایی سبک‌وزن و تک‌منظوره هستند که اطلاعات مختلفی مانند لاگ فایل‌ها، وضعیت سیستم، ترافیک شبکه و وضعیت سرویس‌ها را جمع‌آوری کرده و معمولاً به Fluentd یا مستقیم به Elasticsearch ارسال می‌کنند. این ابزارها در کنار هم یک استک قدرتمند و مقیاس‌پذیر برای مانیتورینگ و تحلیل لاگ‌ها تشکیل می‌دهند.  
  </p>
</details>
<details>
  <summary>Kibana (نمایش، فیلتر و مانیتورینگ لاگ‌ها)  </summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>Fluentd (جمع آموری و پردازش لاگ ها)  </summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>Logstash (وقتی پردازش سنگین‌تری لازمه) </summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>Beats</summary>
  <p>
    <!-- SMD -->
    ▫️Filebeat (جمع‌آوری لاگ‌های مانند Apache/nginx logs، PHP error logs, ...)  
    ▫️Metricbeat (جمع‌آوری متریک‌های سیستم و پایگاه داده مانند CPU، RAM، query load, ...)  
    ▫️Packetbeat (ضبط و تحلیل ترافیک لایه شبکه و اپلیکیشن مانند HTTP, MySQL, DNS, ... )  
    ▫️Heartbeat (پینگ و بررسی وضعیت سلامت سرویس‌ها)  
    ▫️Auditbeat (بررسی امنیتی سیستم: تغییرات فایل، یوزرها، دسترسی‌ها)  
  </p>
</details>

برای نصب ابزارهای لاگ در صورت نیاز از دستور زیر استفاده کنید
```bash
cd logs
sudo docker compose up -d
```

جهت مشاهده لاگ ها به آدرس زیر بروید
```
http://kibana:5601/
```

---



---

### 🦊 ساخت Token برای اتصال به GitLab
<details>
  <summary>GitLab</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

جهت دریافت توکت در گیت لب به مسیر زیر بروید
```
GitLab >> Preferences >> Access tokens >> Add new token
```
و توکن بدست امده را در فایل inventory_file.yml و در متغیر gitlab_token بنویسید

---

### 🛠️ DevSecOps
<details>
  <summary>DevSecOps</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

![DevSecOps](./img/devsecops.jpg)

---

### 🛠️ Cloud Providers
<details>
  <summary>AWS</summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>Azure</summary>
  <p>
    <!-- SMD -->
  </p>
</details>
<details>
  <summary>GCP</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

---

### 🛠️ اتوماسیون سازی با n8n
<details>
  <summary>n8n</summary>
  <p>
    <!-- SMD -->
  </p>
</details>

---

### 🛠️ سایر
<details>
  <summary>نصب ابزارهای مورد نیاز</summary>
  
    ```bash
    sudo apt update
    sudo apt-get install cron
    sudo apt install gzip
    sudo apt install tar
    sudo apt install curl
    sudo apt install mysql-client
    sudo apt install postgresql-client
    ```

</details>
<details>
  <summary>راهنماهای مورد نیاز برای مهندسین دواپس</summary>
  
    * [Agile](/cheatsheet/agile.md)
    * [Scrum](/cheatsheet/scrum.md)
    * [Git](/cheatsheet/git.md)
    * [Docker](/cheatsheet/docker.md)
    * [Docker Compose](/cheatsheet/docker-compose.md)
    * [Dockerfile](/cheatsheet/dockerfile.md)
    * [Bash](/cheatsheet/bash.md)
    * [Yaml](/cheatsheet/yaml.md)
    * [Marrkdown](/cheatsheet/marrkdown.md)

</details>

### 🛠️ نصب ابزارهای مورد نیاز
```bash
sudo apt update
sudo apt-get install cron
sudo apt install gzip
sudo apt install tar
sudo apt install curl
sudo apt install mysql-client
sudo apt install postgresql-client
```

---

### 🛠️ راهنماهای مورد نیاز برای مهندسین دواپس
* [Agile](/cheatsheet/agile.md)
* [Scrum](/cheatsheet/scrum.md)
* [Git](/cheatsheet/git.md)
* [Docker](/cheatsheet/docker.md)
* [Docker Compose](/cheatsheet/docker-compose.md)
* [Dockerfile](/cheatsheet/dockerfile.md)
* [Bash](/cheatsheet/bash.md)
* [Yaml](/cheatsheet/yaml.md)
* [Marrkdown](/cheatsheet/marrkdown.md)

---

### 🛠️ نقشه راه یادگیری DevOps
![DevOps](./img/devops2.jpg)

