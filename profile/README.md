<p align="center">
  <img src="https://avatars.githubusercontent.com/u/177096638?v=4" width="112" alt="LDS logo">
</p>

<h1 align="center">LDS · Laboratory of Digital Solutions</h1>

<p align="center">
  Independent open-source lab building digital services for education.<br>
  Независимая open-source лаборатория: цифровые сервисы для образования.
</p>

<p align="center">
  <a href="#english">English</a> · <a href="#русский">Русский</a>
</p>

---

## English

We design, build and run software for universities and colleges: from applicant and student
services to the shared platform underneath them. Reusable parts are published as open source.

### What we work on

- **Personal accounts** for students and staff: records, statements, requests, schedules, payslips
- **Admissions**: applications, competitive lists, enrollment orders, queue screens
- **Integration platform**: an event bus on Kafka with CloudEvents, transactional outbox and inbox
- **Identity and access**: sign-in, verification, role-based permissions
- **Operations**: status pages and metrics on Prometheus, blue-green deploys
- **Applied AI**: extracting data from documents and images

### Open source

| Project | What it is |
| --- | --- |
| [deploy-kit](https://github.com/ldslab/deploy-kit) | Blue-green deploys for JVM services behind Caddy, packaged as GitHub Actions with a stub-driven test harness |

### Stack

Kotlin · Spring Boot · Angular · TypeScript · PostgreSQL · Kafka · Redis · Caddy · Tauri · GitHub Actions

### How we work

- Pull requests stay small enough to review in twenty minutes; we merge them with green CI and a code owner's approval.
- A fixed defect comes with a test that fails without the fix.
- A red main branch is fixed before anything else.
- Secrets and personal data never enter git; a leaked secret is rotated, not just deleted.

### Contributing and security

Start with [CONTRIBUTING.md](https://github.com/ldslab/.github/blob/main/CONTRIBUTING.md).
Report vulnerabilities privately as described in
[SECURITY.md](https://github.com/ldslab/.github/blob/main/SECURITY.md), never in public issues.

---

## Русский

Проектируем, разрабатываем и сопровождаем программные решения для вузов и колледжей: от сервисов
для абитуриентов и студентов до общей платформы под ними. Переиспользуемые части публикуем
в открытом доступе.

### Чем занимаемся

- **Личные кабинеты** студентов и сотрудников: успеваемость, ведомости, заявления, расписание, расчётные листки
- **Приёмная кампания**: приём документов, конкурсные списки, приказы о зачислении, экраны электронной очереди
- **Интеграционная платформа**: событийная шина на Kafka с CloudEvents, transactional outbox и inbox
- **Идентификация и доступ**: вход, верификация, ролевая модель прав
- **Эксплуатация**: страницы статуса и метрики на Prometheus, blue-green выкладка
- **Прикладной ИИ**: извлечение данных из документов и изображений

### Открытые проекты

| Проект | Что это |
| --- | --- |
| [deploy-kit](https://github.com/ldslab/deploy-kit) | Blue-green выкладка JVM-сервисов за Caddy в виде GitHub Actions, с тестовым стендом на заглушках |

### Стек

Kotlin · Spring Boot · Angular · TypeScript · PostgreSQL · Kafka · Redis · Caddy · Tauri · GitHub Actions

### Как работаем

- Pull request читается за двадцать минут; мержим его с зелёным CI и одобрением владельца кода.
- Исправленный дефект закрывается тестом, который без исправления падает.
- Красная основная ветка чинится первой.
- Секреты и персональные данные в git не попадают; утёкший секрет ротируется, а не просто удаляется.

### Участие и безопасность

Начните с [CONTRIBUTING.md](https://github.com/ldslab/.github/blob/main/CONTRIBUTING.md).
Об уязвимостях сообщайте закрыто, как описано в
[SECURITY.md](https://github.com/ldslab/.github/blob/main/SECURITY.md), а не в публичных issue.
