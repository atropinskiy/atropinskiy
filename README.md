<div align="center">

# Александр Тропинский

### **Team Lead | System Architect | Full-Stack & Mobile Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Telegram](https://img.shields.io/badge/Telegram-Chat-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/atropinskiy)

</div>

---

### 👨‍💻 Обо мне

Выпускник **Московского Энергетического Института (МЭИ, АВТИ)** по направлению автоматики и вычислительной техники.

Мой профессиональный бэкграунд сочетает **7 лет управленческого опыта** и **6+ лет глубокой инженерной и аналитической экспертизы**. Как **Team Lead и System Architect**, я соединяю бизнес-цели и техническую реализацию:

- Проектирую масштабируемую архитектуру распределенных веб- и мобильных систем (**FastAPI, Next.js, Django, Swift / iOS**).
- Выстраиваю эффективные процессы разработки в команде, CI/CD пайплайны и культуру надежности кода.
- Создаю корпоративные SaaS-решения, CRM, аналитические платформы и мобильные приложения с акцентом на бизнес-результат и чистый UX/UI.

---

### 🛠 Технологический стек

<div align="center">

| Категория                     | Технологии                                                                                    |
| :---------------------------- | :-------------------------------------------------------------------------------------------- |
| **Architecture & Leadership** | System Design, Microservices, Domain-Driven Design (DDD), Agile/Scrum, Code Review, Mentoring |
| **Backend**                   | Python, FastAPI, Django, Django REST Framework, Node.js, Celery, Redis                        |
| **Frontend**                  | TypeScript, JavaScript, Next.js, React, HTML5 / SCSS, Tailwind CSS, Plotly.js                 |
| **Mobile (iOS)**              | Swift, SwiftUI, UIKit, MVVM, Clean Architecture, Combine                                      |
| **Databases & ORM**           | PostgreSQL, MySQL, SQLAlchemy, Django ORM, Redis                                              |
| **DevOps & Cloud**            | Docker, Docker Compose, GitHub Actions, CI/CD, Nginx, Linux (Ubuntu), Bash                    |
| **Data & Analytics**          | Pandas, NumPy, Scikit-learn, Matplotlib, Data Pipelines & Web Scraping                        |

</div>

---

## 🚀 Архитектура и ключевые проекты

> Проектирование и разработка **Opt-One** — распределенной B2B E-commerce, Mobile & FinTech экосистемы для оптовой торговли электроникой, мониторинга цен, проведения торгов и мультивалютного финансового учета.

<div align="center">

| Модуль платформы         | Бизнес-назначение                                   | Ключевой стек                                                                       |
| :----------------------- | :-------------------------------------------------- | :---------------------------------------------------------------------------------- |
| 💼 **Opt-one.online**    | SaaS-мониторинг цен, аналитика маржинальности и CRM | `Django` • `Plotly.js` • `PostgreSQL` • `Docker` • `Docker Compose`                 |
| 🤝 **Opt-one Partners**  | B2B-портал партнерских торгов, тендеров и офферов   | `React` • `RTK Query` • `Django` • `WebSocket` • `AI` • `Docker` • `Docker Compose` |
| 💳 **Opt-one Wallet**    | Казначейство, трансграничные платежи и 1С           | `React` • `Redux` • `Chakra UI` • `DRF` • `1C API` • `Docker` • `Docker Compose`    |
| 📱 **MasterStats (iOS)** | Мобильное приложение анализа трендов цен и закупок  | `Swift` • `SwiftUI` • `Combine` • `Charts` • `Docker` • `Docker Compose`            |

</div>

---

### 1. 💼 Opt-one.online — B2B SaaS платформа закупок, мониторинга цен и CRM

> **Роль:** System Architect / Lead Full-Stack Developer  
> **Стек:** `Python` • `Django` • `Plotly.js` • `SCSS` • `PostgreSQL` • `OAuth 2.0` • `Docker` • `Docker Compose`

**Opt-one** — комплексная облачная SaaS-платформа для управления оптовыми поставками электроники, сквозного мониторинга цен и контроля бизнес-процессов дистрибуции.

#### 🌟 Ключевые возможности и архитектурные решения:

- **Price Intelligence & Analytics:** Интерактивные многомерные графики (Plotly) динамики рыночных цен, плотности предложений и аналитики маржинальности с учетом таможенных моделей (DDP, DDP с НДС, Гонконг, Китай).
- **Автоматизация обработки спецификаций (PL Parser):** Сервис парсинга и сопоставления разноформатных Excel/PL файлов в единую номенклатуру каталога.
- **Финансово-операционный CRM-контур:** Управление цепочками инвойсов, учет оплат, контроль распределения товаров и мультивалютный пересчет.
- **Безопасность и разграничение прав:** Интеграция OAuth 2.0 и гранулярная ролевая модель (RBAC) для отделов продаж, логистики и менеджмента.

<br>

<div align="center">
  <table width="100%" border="0" cellspacing="0" cellpadding="0" align="center">
    <thead>
      <tr align="center">
        <th width="50%"><b>🖥 Монитор аналитики: Графики динамики цен и распределения</b></th>
        <th width="50%"><b>🖥 Монитор операционного контура: Управление заказами и PL</b></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/opt-one.online/screenshots/dash.png">
            <img src="sites/opt-one.online/screenshots/dash.png" alt="Opt-one Price Analytics Dashboard" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Аналитика динамики цен и предложений поставщиков (Plotly)</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/opt-one.online/screenshots/orders.png">
            <img src="sites/opt-one.online/screenshots/orders.png" alt="Opt-one Orders & Packing Lists" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Управление заказами, инвойсами и статусами автопарсинга PL</i></sub>
        </td>
      </tr>
    </tbody>
  </table>
</div>

---

### 2. 🤝 Opt-one Partners — B2B SaaS портал партнерских закупок, тендеров и фин. учета

> **Роль:** System Architect / Lead Full-Stack Developer  
> **Стек:** `React` • `RTK Query` • `Django` • `Tailwind CSS` • `shadcn/ui` • `WebSocket` • `Celery` • `Redis` • `PostgreSQL` • `OpenRouter API` • `Docker` • `Docker Compose` • `HttpOnly Cookie`

**Opt-one Partners** — многофункциональная SaaS-платформа для взаимодействия с B2B-партнерами, автоматизированного проведения тендеров, сбора офферов, парсинга цен и сквозного финансового учета.

#### 🌟 Ключевые возможности и архитектурные решения:

- **Тендерный модуль и управление офферами:** Проведение закупочных процедур в реальном времени, автоматический скоринг предложений поставщиков, определение победителей и распределение объемов партий.
- **Интерактивная аналитика и мультивалютный трекинг:** Мониторинг кросс-курсов валют (USD, EUR, AED, CNY) в режиме реального времени, нормализованные и абсолютные графики динамики цен по моделям, анализ плотности и структуры предложений по неделям.
- **Финансово-казначейский контур:** Контроль статусов инвойсов, балансов кошельков, поэтапных оплат, отслеживание задолженностей и автоматическое формирование распределений платежей.
- **Реактивная архитектура и высокая отзывчивость:** Real-time доставка обновлений и статусов через WebSockets, асинхронная обработка тяжелых задач (парсинг, отчеты) в фоновых воркерах Celery + Redis с многоуровневым кэшированием.
- **AI-интеграция (OpenRouter API):** Подключение LLM-моделей для интеллектуального анализа данных, обработки неструктурированных спецификаций и генерации таргетов.
- **Безопасность корпоративного уровня:** Защита сессий и токенов с использованием HttpOnly Cookie, ролевая изоляция данных и аудит действий.

<br>

<div align="center">
  <table width="100%" border="0" cellspacing="0" cellpadding="0" align="center">
    <thead>
      <tr align="center">
        <th width="50%"><b>🖥 Панель управления менеджера: Тендеры, офферы и инвойсы</b></th>
        <th width="50%"><b>🖥 Монитор аналитики: Динамика цен, курсы валют и статистика</b></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/partners/screen_shots/main.png">
            <img src="sites/partners/screen_shots/main.png" alt="Partners Manager Dashboard & Tenders" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Рабочее место менеджера: контроль тендеров, офферов, оплат и инвойсов</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/partners/screen_shots/dash.png">
            <img src="sites/partners/screen_shots/dash.png" alt="Partners FX & Price Dynamics Analytics" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Аналитический дашборд: курсы валют, динамика цен и объем предложений</i></sub>
        </td>
      </tr>
    </tbody>
  </table>
</div>

---

### 3. 💳 Opt-one Wallet — SaaS система трансграничных платежей, казначейства и учета

> **Роль:** System Architect / Lead Full-Stack Developer  
> **Стек:** `React` • `Redux` • `RTK Query` • `Django` • `REST API` • `Chakra UI` • `PostgreSQL` • `Docker` • `Docker Compose` • `1C Integration` • `Bank Statement Parsers`

**Opt-one Wallet** — специализированный финансово-казначейский SaaS-сервис для автоматизации международных расчетов, учета мультивалютных потоков, консолидации банковских выписок и синхронизации с корпоративными системами учета (1С).

#### 🌟 Ключевые возможности и архитектурные решения:

- **Мультивалютное казначейство и балансы (Treasury Dashboard):** Сквозной мониторинг фактических остатков, ожидаемых поступлений и обязательств к погашению в разрезе валют (RUB, AED, USDT, CNY) и контрагентов.
- **Управление международными платежами и переводами:** Проведение и контроль цепочек трансграничных оплат поставщикам, учет конвертаций, фиксация курсовой разницы и балансов взаиморасчетов.
- **Парсер банковских выписок и консолидация:** Автоматический импорт и нормализация разноформатных банковских выгрузок в единую аналитическую панель с сопоставлением платежных поручений.
- **Интеграция с 1С и учетными системами:** Двусторонний обмен данными по заявкам на оплату, закрывающим документам, контрагентам и фактическим проводкам.
- **Контроль обязательств и сделок:** Модуль ведения заявок на импорт, обязательств перед партнерами и исполнителями с гибкой фильтрацией и экспортом отчетов (`.xlsx`).

<br>

<div align="center">
  <table width="100%" border="0" cellspacing="0" cellpadding="0" align="center">
    <thead>
      <tr align="center">
        <th width="50%"><b>🖥 Казначейский дашборд: Мультивалютные балансы и ликвидность</b></th>
        <th width="50%"><b>🖥 Операционный контур: Заявки на импорт и обязательства</b></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/opt-one.wallet/screenshots/image.png">
            <img src="sites/opt-one.wallet/screenshots/image.png" alt="Opt-one Wallet Treasury Dashboard" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Финансовый дашборд: фактические и ожидаемые остатки (RUB, AED, USDT, CNY)</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 10px;">
          <a href="sites/opt-one.wallet/screenshots/image%20copy.png">
            <img src="sites/opt-one.wallet/screenshots/image%20copy.png" alt="Opt-one Wallet Imports & Obligations" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Управление заявками на импорт, реестр обязательств и экспорт отчетов</i></sub>
        </td>
      </tr>
    </tbody>
  </table>
</div>

---

### 4. 📱 MasterStats (iOS) — Мобильное приложение аналитики цен, трендов и закупок

> **Роль:** Lead iOS & Mobile System Architect  
> **Стек:** `Swift` • `SwiftUI` • `Combine` • `Charts` • `MVVM` • `Clean Architecture` • `REST API` • `Docker` • `Docker Compose`

**MasterStats** — нативное iOS-приложение для оперативного анализа рыночных трендов цен электроники, мониторинга объема предложений поставщиков и принятия обоснованных решений по закупкам в режиме реального времени.

#### 🌟 Ключевые возможности и архитектурные решения:

- **Аналитика трендов и динамики рынка:** Выявление ключевых ценовых колебаний, расчет средних цен и автоматическое определение лидеров роста и падения (Top 5 Grow / Top 5 Fall).
- **Интерактивные графики (SwiftUI Charts):** Недельный мониторинг средней стоимости и плотности распределения партий по выбранным конфигурациям устройств.
- **Инструменты принятия решений о закупках:** Гранулярная фильтрация по периодам, моделям (iPhone 13–16 Pro/Max) и региональным спецификациям (включая китайский рынок) для точного расчета таргетов.
- **Нативная реактивная архитектура:** Высокая производительность и мгновенный отклик интерфейса на базе Swift, SwiftUI, Combine и Clean Architecture / MVVM.

<br>

<div align="center">
  <table width="100%" border="0" cellspacing="0" cellpadding="0" align="center">
    <thead>
      <tr align="center">
        <th width="25%"><b>📱 Аналитический дашборд</b></th>
        <th width="25%"><b>📱 Тренды по моделям</b></th>
        <th width="25%"><b>📱 Монитор цен (Top Prices)</b></th>
        <th width="25%"><b>📱 Фильтры и спецификации</b></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" valign="top" style="padding: 5px;">
          <a href="sites/masterstats/screens/image%20copy%202.png">
            <img src="sites/masterstats/screens/image%20copy%202.png" alt="MasterStats iOS Dashboard & Trends" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Дашборд: динамика цен, Top 5 роста и падения</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 5px;">
          <a href="sites/masterstats/screens/image%20copy%203.png">
            <img src="sites/masterstats/screens/image%20copy%203.png" alt="MasterStats Model Analytics" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Недельная динамика цен и объемов (SwiftUI Charts)</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 5px;">
          <a href="sites/masterstats/screens/image.png">
            <img src="sites/masterstats/screens/image.png" alt="MasterStats Top Prices" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Список лучших цен и остатков по моделям</i></sub>
        </td>
        <td align="center" valign="top" style="padding: 5px;">
          <a href="sites/masterstats/screens/image%20copy.png">
            <img src="sites/masterstats/screens/image%20copy.png" alt="MasterStats Filters" width="100%" style="border-radius: 8px; border: 1px solid #30363d;" />
          </a>
          <br>
          <sub><i>Многоуровневая фильтрация моделей и дат</i></sub>
        </td>
      </tr>
    </tbody>
  </table>
</div>

---
