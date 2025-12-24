---
name: virtualization-vmware-expert
description: Эксперт по виртуализации и VMware
activation:
  - выбран как эксперт в seo-wizard
---

# Virtualization & VMware Expert Skill

Роль эксперта по виртуализации и VMware для генерации экспертного контента.

---

## EXPERT PROFILE

```yaml
name: Эксперт по виртуализации и VMware
role: Специалист по технологиям виртуализации, миграции и облачной инфраструктуре
expertise:
  - VMware vSphere, vCenter, ESXi
  - VMware Cloud Foundation (VCF) и vSphere Foundation (VVF)
  - vSAN и NSX (сеть и хранилище)
  - Миграция с VMware на альтернативные платформы
  - Российские платформы виртуализации (zVirt, vStack, Базис)
  - Proxmox VE, Nutanix AHV, KVM
  - Гиперконвергентная инфраструктура (HCI)
  - Software Defined Data Center (SDDC)
  - Импортозамещение и compliance
tone: Профессиональный, технически грамотный, практико-ориентированный
```

---

## АКТУАЛЬНЫЕ НОВОСТИ И ТРЕНДЫ 2024-2025

### Изменения VMware после приобретения Broadcom

```yaml
broadcom_acquisition:
  date: "Ноябрь 2023"
  price: "69 млрд долларов"

  key_changes_2024:
    - "56 продуктов VMware получили статус End Of Availability (EOA)"
    - "Прекращено распространение бесплатных версий ESXi 7.x и 8.x"
    - "Остановлена продажа новых бессрочных лицензий"
    - "Переход на подписную модель лицензирования"
    - "Фокус на двух продуктах: VCF и VVF"

  key_changes_2025:
    - "С 10 апреля 2025: прекращена поддержка бессрочных лицензий"
    - "Минимум 72 ядра на покупку (вместо 16)"
    - "Лицензирование по ядрам CPU вместо сокетов"
    - "Сокращение партнёрской сети VCSP с 4500+ до ~13"
    - "31 октября 2025: завершение программы White Label"

  positive_changes:
    - "Возвращение бесплатного гипервизора VMware ESXi"
    - "Бесплатные лицензии на VMware vSAN"
    - "Бесплатные лицензии для VCP-сертифицированных специалистов"

  price_impact:
    - "Рост цен на vSphere, NSX, vSAN в 3-6 раз"
    - "Некоторые клиенты в Европе: увеличение до 1500%"
    - "AT&T: рост на 1050%"

  support_end_dates:
    vsphere_7x:
      end_of_general_support: "2 октября 2025"
      status: "После этой даты Broadcom не выпускает патчи безопасности"
      note: "Только technical guidance без исправлений уязвимостей"
    vsphere_8x:
      end_of_general_support: "11 октября 2027"
      technical_guidance: "До 2029 года без фиксов уязвимостей"
      note: "Новая платформа с 'детскими болячками' + отсутствие поддержки в РФ"
```

### VMware в России

```yaml
vmware_russia_status:
  suspension_date: "После 2022 года"
  suspended_operations:
    - "Продажи"
    - "Техническая поддержка"
    - "Профессиональные сервисы"

  implications:
    legal:
      - "Невозможно легально закупить новые лицензии"
      - "Нет официального канала поддержки"
      - "Сложно доказать регулятору 'разумные меры' при инциденте"
    technical:
      - "Нет доступа к патчам безопасности"
      - "Невозможно полноценно участвовать в партнёрских программах"
      - "Легальный путь обновления до VCF практически закрыт"

  customer_options:
    - option: "Оставаться на стареющем стеке"
      risk: "Без официальной поддержки и патчей"
    - option: "Сложные схемы получения подписок"
      risk: "Юридические и технические риски"
    - option: "Планомерный выход из VMware-зависимости"
      risk: "Минимальный — управляемый проект"

  statistics:
    current_usage: "58% российских компаний в 2025 году продолжают использовать VMware"
    source: "Исследование «Код Безопасности»"
```

### Массовый исход с VMware

```yaml
vmware_exodus:
  survey_data:
    foundry_cio: "56% предприятий планируют сократить использование VMware"
    active_alternatives: "71% активно ищут on-premises альтернативы"
    considering_alternatives: "98% клиентов VMware рассматривают или используют альтернативы"

  gartner_predictions:
    statement: "Рынок серверной виртуализации переживает самый значительный разрыв за десятилетия"
    by_2028: "70% корпоративных клиентов VMware мигрируют 50% рабочих нагрузок"
    workload_loss: "VMware потеряет 35% рабочих нагрузок"
```

### VMware Cloud Foundation 9.0 (2025)

```yaml
vcf_9_0:
  release: "2025"
  key_features:
    - "Унифицированная платформа для VM и Kubernetes"
    - "VMware Cloud Foundation Operations — обязательный компонент"
    - "SDDC Manager объявлен устаревшим"
    - "VCF Intelligent Assist — AI-инсайты"
    - "OpenAI-совместимый API для разработчиков"
    - "Model Context Protocol для Agentic AI"

  sovereignty_features:
    - "Теги резидентности данных"
    - "Гео-фенсинг"
    - "Автоматическая ротация сертификатов"

  upgrade_path:
    from_5x: "Прямое обновление до 9.0"
    from_4x: "Сначала обновление до 5.x"
    from_3x: "Миграция NSX-V → NSX-T, затем 4.x → 5.x → 9.0"

  requirements:
    - "Переход с baseline на vLCM образы"
    - "Baseline больше не поддерживаются"
```

### Российский рынок виртуализации

```yaml
russian_market_2025:
  market_share:
    domestic_vendors: "60.2% (2024, рост с 26.2% в 2021)"
    adoption_rate: "30%+ предприятий используют российские системы"

  market_size:
    2025: "19 млрд рублей (прогноз)"
    2031: "51.4 млрд рублей (прогноз)"
    cagr: "17.9%"

  regulatory:
    kii_deadline: "1 января 2025 — запрет иностранного ПО на КИИ"
    affected: "Заказчики со значимыми объектами КИИ (кроме муниципальных)"
    virtualization_2026: "С 2026 года ужесточаются требования по виртуализации в реестре Минцифры"

  trends:
    - "Снижение зависимости от зарубежных решений"
    - "Рост спроса на AI/ML инфраструктуру"
    - "Повышение требований к безопасности"
    - "Импортозамещение"
```

### Регуляторика и персональные данные

```yaml
regulatory_framework:
  federal_law_152fz:
    name: "152-ФЗ «О персональных данных»"
    scope: "Обработка персональных данных граждан РФ"
    requirements:
      - "Локализация хранения ПДн в России"
      - "Обеспечение безопасности обработки"
      - "Уведомление Роскомнадзора"

  government_decree_1119:
    name: "ПП РФ № 1119"
    scope: "Требования к защите ПДн при их обработке в ИСПДн"
    levels: "4 уровня защищённости (УЗ-1 — УЗ-4)"

  fstec_order_17:
    name: "Приказ ФСТЭК № 17"
    scope: "Меры защиты в зависимости от уровня защищённости ИСПДн"
    applies_to: "Государственные информационные системы"

  mindigital_registry:
    name: "Реестр российского ПО (reestr.digital.gov.ru)"
    requirement: "С 2026 года — ужесточение требований по виртуализации"
    affected: "Критичная инфраструктура и госсектор"

  ispdn_attestation:
    what_is_checked:
      - "Гостевая ОС"
      - "Платформа и гипервизор"
      - "Средства виртуализации"
      - "Юридический статус ПО"
      - "Наличие поддержки"
      - "Предсказуемость поставщика"

    vmware_problems:
      - "VMware не продаётся и не поддерживается в РФ официально"
      - "Гипервизор VMware не в реестре Минцифры"
      - "При инциденте сложно доказать регулятору 'разумные меры'"
      - "Даже российская гостевая ОС внутри VMware не снимает вопрос о гипервизоре"

    key_point: "Гипервизор — самое узкое место при аттестации ИСПДн на VMware"

  new_industry_standard:
    old: "VMware — 'отраслевой стандарт'"
    new: "Стандарт в России — стек, который:"
    criteria:
      - "Официально продаётся и поддерживается в стране"
      - "Укладывается в регуляторные требования"
      - "Имеет понятную долгосрочную перспективу"
      - "Находится в российской юрисдикции"
      - "Соответствует политике импортозамещения"
      - "Имеет дорожную карту и команду разработки в России"
```

---

## VMWARE TECHNOLOGIES

### VMware vSphere & ESXi

```yaml
vsphere:
  description: Платформа серверной виртуализации корпоративного уровня
  components:
    - ESXi: "Bare-metal гипервизор Type 1"
    - vCenter Server: "Централизованное управление"
    - vMotion: "Live-миграция ВМ без простоя"
    - Storage vMotion: "Миграция хранилища"
    - HA: "High Availability — автоматический перезапуск ВМ"
    - DRS: "Distributed Resource Scheduler — балансировка нагрузки"
    - FT: "Fault Tolerance — непрерывная доступность"

  versions:
    current: "vSphere 8.x"
    vcf_9: "Включён в VCF 9.0 и VVF 9.0"

  licensing_changes:
    old: "По сокетам, минимум 16 ядер"
    new: "По ядрам CPU, минимум 72 ядра"

  keywords:
    - vSphere
    - ESXi
    - vCenter
    - гипервизор VMware
    - виртуализация серверов
    - vMotion
    - DRS
    - HA
```

### VMware vSAN

```yaml
vsan:
  description: Программно-определяемое хранилище для гиперконвергентной инфраструктуры

  architecture:
    types:
      - "Гибридный: SSD (кэш) + HDD (ёмкость)"
      - "All-Flash: только SSD/NVMe"
    performance: "До 150 000 IOPS на узел"
    latency: "Доли миллисекунды"

  features:
    - "Интеграция с vSphere"
    - "Распределённое хранилище на уровне кластера"
    - "Политики хранения (Storage Policies)"
    - "Deduplication и compression"
    - "Erasure coding"
    - "Stretched clusters"

  compatibility:
    - vMotion
    - Storage vMotion
    - HA
    - DRS
    - SRM
    - vSphere Replication
    - Snapshots
    - VADP
    - Horizon View

  keywords:
    - vSAN
    - гиперконвергентная инфраструктура
    - HCI
    - программно-определяемое хранилище
    - SDS
    - All-Flash
```

### VMware NSX

```yaml
nsx:
  description: Программно-определяемая сеть (SDN) для виртуальных машин

  versions:
    nsx_v:
      status: "End of Life"
      note: "Заточен под vSphere, управление из vCenter"
    nsx_t:
      status: "Актуальная версия"
      features:
        - "Мультиплатформенный"
        - "Независимая консоль управления"
        - "Не требует vCenter"
        - "Поддержка vSphere и KVM"
        - "OpenStack, Kubernetes, Docker, AWS"

  capabilities:
    - "Микросегментация"
    - "Distributed Firewall"
    - "Load Balancing"
    - "VPN"
    - "NAT"
    - "Logical switching"
    - "Logical routing"

  architecture:
    - "Management Plane"
    - "Control Plane"
    - "Data Plane"

  keywords:
    - NSX
    - NSX-T
    - SDN
    - программно-определяемая сеть
    - микросегментация
    - сетевая виртуализация
```

### VMware Cloud Foundation (VCF)

```yaml
vcf:
  description: Интегрированная платформа SDDC (Software Defined Data Center)

  components:
    - vSphere: "Серверная виртуализация"
    - vSAN: "Программно-определяемое хранилище"
    - NSX: "Программно-определяемая сеть"
    - SDDC Manager: "Автоматизация и lifecycle management"
    - vRealize Suite: "Управление операциями"
    - Aria Suite: "Облачное управление"

  current_version: "VCF 9.0.1 (2025)"

  new_features_9_0:
    - "VCF Operations — обязательный компонент"
    - "VCF Intelligent Assist (AI)"
    - "Kubernetes интеграция"
    - "VM Service"
    - "Data sovereignty features"

  use_cases:
    - "Частное облако"
    - "Гибридное облако"
    - "Модернизация приложений"
    - "Контейнеризация"

  keywords:
    - VMware Cloud Foundation
    - VCF
    - SDDC
    - частное облако
    - гиперконвергентная инфраструктура
```

### VMware vSphere Foundation (VVF)

```yaml
vvf:
  description: Облегчённая версия VCF для базовой виртуализации

  includes:
    - vSphere Enterprise Plus
    - vSAN Enterprise
    - Aria Operations
    - Aria Operations for Logs

  excludes:
    - NSX
    - SDDC Manager
    - vRealize Automation

  target: "Организации с базовыми потребностями виртуализации"

  keywords:
    - vSphere Foundation
    - VVF
    - виртуализация
    - vSphere Enterprise
```

---

## VMWARE ALTERNATIVES

### Proxmox VE

```yaml
proxmox:
  description: Open-source платформа виртуализации на базе KVM и LXC
  license: "AGPL v3 (бесплатно)"

  features:
    - "KVM для виртуальных машин"
    - "LXC для контейнеров"
    - "Единый веб-интерфейс"
    - "Live-миграция"
    - "High Availability"
    - "Ceph интеграция"
    - "ZFS поддержка"

  vmware_migration:
    - "Мастер импорта VM с ESXi (версия 8.x)"
    - "Автоматическая конвертация дисков"
    - "Поддержка OVA/OVF"

  new_2025:
    - "Proxmox Datacenter Manager"
    - "Централизованное управление несколькими кластерами"

  pros:
    - "Бесплатно"
    - "Open-source"
    - "Низкие требования к оборудованию"
    - "Активное сообщество"

  cons:
    - "Требует инженерной экспертизы"
    - "Не enterprise-ready 'из коробки'"

  keywords:
    - Proxmox
    - Proxmox VE
    - KVM
    - LXC
    - open-source виртуализация
```

### Nutanix AHV

```yaml
nutanix:
  description: Проприетарный гипервизор в составе HCI-платформы Nutanix

  architecture:
    - "Основан на KVM"
    - "Тесная интеграция с Nutanix HCI"
    - "Управление через Prism UI"

  features:
    - "Hyperconverged Infrastructure"
    - "Unified storage"
    - "One-click operations"
    - "Nutanix Move (инструмент миграции)"

  vmware_comparison:
    replaces: "vSphere + vSAN + NSX"
    management: "Prism (вместо vCenter)"

  pros:
    - "Готовое HCI-решение"
    - "Простота управления"
    - "Автоматизированная миграция с VMware"

  cons:
    - "Vendor lock-in"
    - "Высокая стоимость"

  keywords:
    - Nutanix
    - AHV
    - HCI
    - гиперконвергентная инфраструктура
    - Prism
```

### Microsoft Hyper-V

```yaml
hyperv:
  description: Гипервизор Microsoft, включённый в Windows Server

  licensing:
    - "Включён в Windows Server"
    - "Бесплатный Hyper-V Server (standalone)"

  features:
    - "Live Migration"
    - "Storage Migration"
    - "Failover Clustering"
    - "Replica"
    - "Shielded VMs"

  management:
    - "Hyper-V Manager"
    - "System Center VMM"
    - "Windows Admin Center"

  pros:
    - "Включён в Windows Server"
    - "Интеграция с Active Directory"
    - "Знакомый для Windows-администраторов"

  cons:
    - "Ограниченная поддержка Linux"
    - "Зависимость от экосистемы Microsoft"

  keywords:
    - Hyper-V
    - Microsoft
    - Windows Server
    - виртуализация Microsoft
```

### KubeVirt

```yaml
kubevirt:
  description: Виртуальные машины в Kubernetes

  concept:
    - "VM как Kubernetes ресурс"
    - "Единое управление контейнерами и VM"
    - "Kubernetes orchestration для VM"

  adoption_2025: "Многократный рост использования (по данным Red Hat)"

  use_cases:
    - "Модернизация legacy-приложений"
    - "Гибридные workloads"
    - "Контейнеризация с сохранением VM"

  keywords:
    - KubeVirt
    - Kubernetes
    - виртуальные машины в Kubernetes
    - контейнеризация
```

---

## VK CLOUD КАК АЛЬТЕРНАТИВА VMWARE

### О платформе VK Cloud

```yaml
vk_cloud:
  description: Российская универсальная облачная платформа для бизнеса и разработки

  history:
    previous_names:
      - "Mail.ru Cloud Solutions"
      - "VK Cloud Solutions"
    current: "VK Cloud (в составе VK Tech)"
    years_in_production: "Больше 8 лет"
    development_start: "Середина 2010-х"

  key_differentiators:
    - "Не 'ещё одно облако на чужой виртуализации'"
    - "Локальная команда разработки и экспертизы в России"
    - "Архитектура, релизы, исправления — всё внутри страны"
    - "Учёт российских регуляторных требований с самого начала"
    - "Юридически и фактически присутствует в РФ"
    - "Не зависит от внешних санкций — российский вендор"

  vs_vmware:
    vmware: "Вендор ушёл из России, не поддерживает, не продаёт"
    vk_cloud: "Российский вендор с постоянным присутствием"

  regulatory_compliance:
    - "Требования 152-ФЗ и подзаконных актов по защите ПДн"
    - "Политика использования ПО из реестра Минцифры"
    - "Поддержка российских ОС как гостевых и базовых"
    - "Предсказуемый статус для аттестации ИСПДн"
    - "Сертификация по линии ФСТЭК/ФСБ"

  value_proposition:
    - "Не только 'виртуалки и диски'"
    - "Архитектура, изначально спроектированная под российскую регуляторику"
    - "Понятная дорожная карта развития"
    - "Живая команда разработки внутри страны"
```

### Преимущества перехода во VK Cloud

```yaml
migration_benefits:
  risk_reduction:
    technical:
      - "Уход от связки 'новая vSphere 8 + отсутствие поддержки в РФ'"
      - "Избавление от зависимости от иностранного вендора"
      - "Стабильная платформа с локальной поддержкой"
    legal:
      - "Инфраструктура для демонстрации регулятору"
      - "Подтверждение прав использования"
      - "Статус в реестре российского ПО"

  migration_approach:
    type: "Не 'разовый прыжок', а управляемый проект"
    stages:
      - stage: "Инвентаризация"
        description: "Анализ текущего VMware-ландшафта (облако провайдера или собственный ЦОД)"
      - stage: "Проектирование"
        description: "Разработка целевой архитектуры с учётом требований по ПДн, импортозамещению, внутренним политикам"
      - stage: "Миграция dev/test"
        description: "Перенос некритичных нагрузок для отработки процессов"
      - stage: "Миграция бизнес-сервисов"
        description: "Перенос отдельных production-сервисов"
      - stage: "Миграция критичного прода"
        description: "Перенос критически важных систем"
      - stage: "Обучение и адаптация"
        description: "Поддержка по обучению команды и перестройке процессов эксплуатации"

  business_perspective:
    transformation: "Превращает 'страшную историю про конец поддержки VMware' в управляемый проект"
    outcome: "Снижение рисков и обновление ИТ-ландшафта"
    timing: "Чем раньше начать — тем спокойнее пройдут ближайшие годы"
    mode: "Планомерная эволюция вместо пожаротушения"
```

### Типы клиентов для миграции

```yaml
customer_scenarios:
  cloud_vmware_customer:
    description: "Клиент уже в облаке российского провайдера на VMware"
    problems:
      - "vSphere 8 — новая, 'сырая' платформа"
      - "Короткий горизонт поддержки (до 2027)"
      - "Типичные 'детские болячки' новой версии"
      - "Нет вендорской поддержки в стране"
      - "VMware не в реестре Минцифры"
      - "Проблемы с аттестацией ИСПДн"

  onprem_vmware_customer:
    description: "Клиент с on-premise инсталляцией VMware в своём ЦОД"
    problems:
      - "Капиталовложения в собственный железный контур"
      - "vSphere 7.x — End of Support с октября 2025"
      - "vSphere 8.0 — End of Support октябрь 2027"
      - "Perpetual-лицензии больше не продаются"
      - "Легальный путь обновления до VCF закрыт"
    additional_context: "Таймер уже тикает"
```

---

## РОССИЙСКИЕ ПЛАТФОРМЫ ВИРТУАЛИЗАЦИИ

### zVirt (Orion soft)

```yaml
zvirt:
  vendor: "Orion soft"
  description: Российская система управления средой виртуализации

  technology:
    base: "KVM + oVirt"
    type: "oVirt-подобная система"

  features:
    - "Виртуализация серверов, хранилищ, сетей"
    - "Графический интерфейс управления"
    - "Миграция с VMware с минимальными простоями"
    - "Интеграция с Acronis Backup+"
    - "Соответствие российским стандартам безопасности"

  licensing: "По сокетам"

  target: "Средний бизнес, госучреждения"

  certifications:
    - "Реестр отечественного ПО"
    - "ФСТЭК"

  rating: "3-е место (IaaSSaaSPaaS 2024)"

  keywords:
    - zVirt
    - Orion soft
    - российская виртуализация
    - импортозамещение VMware
    - oVirt
```

### vStack

```yaml
vstack:
  vendor: "ITglobal.com"
  description: Производительная enterprise-система виртуализации

  technology:
    hypervisor: "bhyve (FreeBSD)"
    type: "Проприетарная разработка с нуля"
    note: "Значимый контрибьютор в сообщество FreeBSD"

  architecture:
    - "SDC (Software Defined Compute)"
    - "SDN (Software Defined Network)"
    - "SDS (Software Defined Storage)"
    - "Собственный API"

  features:
    - "5+ лет в промышленной эксплуатации"
    - "Легковесность"
    - "Высокая производительность"
    - "Enterprise-функции"

  positioning:
    - "Закрывает задачи 70% пользователей VMware"
    - "Стоимость ниже зарубежных аналогов"

  rating: "5-е место (IaaSSaaSPaaS 2024)"

  keywords:
    - vStack
    - bhyve
    - российская виртуализация
    - импортозамещение
    - ITglobal
```

### Базис (Basis)

```yaml
basis:
  vendor: "Облачная платформа"
  description: Российская платформа виртуализации корпоративного уровня

  products:
    - "Basis Dynamix"
    - "Basis Virtual Security"
    - "Basis VDI"

  features:
    - "CPU Overcommit с гибкими настройками"
    - "Сертификация ФСТЭК"
    - "Автоматизация миграции"

  case_study:
    customer: "Банк ВТБ"
    project: "Масштабное импортозамещение VDI"
    result: "Первый среди крупных банков провёл миграцию на российское решение"

  keywords:
    - Базис
    - Basis
    - VDI
    - российская виртуализация
    - импортозамещение
```

### Другие российские решения

```yaml
other_russian:
  rosa_virtualization:
    base: "oVirt + KVM"
    licensing: "По виртуальным машинам"

  red_virtualization:
    base: "oVirt + KVM"
    vendor: "РЕД СОФТ"

  hostvm:
    base: "oVirt"

  astra_linux:
    note: "Включает средства виртуализации"
    certification: "ФСТЭК, Минобороны"

  horizont_vs:
    vendor: "Горизонт-ВС"

  sharx:
    type: "VDI решение"
```

---

## МИГРАЦИЯ С VMWARE

### Стратегии миграции

```yaml
migration_strategies:
  lift_and_shift:
    description: "Прямой перенос VM без изменений"
    tools:
      - "Proxmox VM Import Wizard"
      - "Nutanix Move"
      - "virt-v2v (libguestfs)"

  replatform:
    description: "Перенос с минимальной адаптацией"
    considerations:
      - "Драйверы virtio"
      - "VMware Tools → open-vm-tools"

  refactor:
    description: "Модернизация при миграции"
    options:
      - "Контейнеризация"
      - "Kubernetes (KubeVirt)"

  replace:
    description: "Полная замена платформы"
    considerations:
      - "Новая инфраструктура"
      - "Переустановка приложений"
```

### Инструменты миграции

```yaml
migration_tools:
  proxmox:
    - "ESXi VM Import Wizard (8.x)"
    - "qm importovf"
    - "qm importdisk"

  nutanix:
    - "Nutanix Move"
    - "Автоматизированная миграция"

  open_source:
    - "virt-v2v"
    - "VMware Converter (устаревший)"

  russian:
    - "zVirt Migration Tools"
    - "vStack Migration"
```

### Рекомендации Gartner

```yaml
gartner_recommendations:
  cost_modeling:
    - "Многолетние модели затрат"
    - "Учёт лицензирования, операционных расходов, масштабирования"

  avoid_lock_in:
    - "Избегать vendor lock-in"
    - "Сохранять гибкость выбора"

  workload_assessment:
    - "Оценка совместимости приложений"
    - "Приоритизация по критичности"
```

---

## СЕРТИФИКАЦИЯ VMWARE

### Уровни сертификации

```yaml
certification_levels:
  vca:
    name: "VMware Certified Associate"
    level: "Начальный"

  vcp:
    name: "VMware Certified Professional"
    level: "Профессиональный"
    target: "Системные администраторы, инженеры"
    experience: "6-12 месяцев практического опыта"
    most_popular: "VCP-DCV (100 000+ сертифицированных специалистов)"

  vcap:
    name: "VMware Certified Advanced Professional"
    level: "Продвинутый"
    tracks:
      - "Design"
      - "Deploy"

  vcdx:
    name: "VMware Certified Design Expert"
    level: "Экспертный"
    format: "Live-защита проекта"
    update_2025: "Ребрендинг для VCF-экспертов"
```

### Направления сертификации

```yaml
certification_tracks:
  dcv:
    name: "Data Center Virtualization"
    focus: "vSphere, ESXi, vCenter"
    exam: "2V0-21.20 (70 вопросов, 130 минут)"

  nv:
    name: "Network Virtualization"
    focus: "NSX"

  dw:
    name: "Digital Workspace"
    focus: "Workspace ONE, Horizon"

  cma:
    name: "Cloud Management and Automation"
    focus: "vRealize/Aria Suite"
```

### Изменения 2025

```yaml
certification_changes_2025:
  free_licenses:
    - "Бесплатные лицензии VMware для VCP-сертифицированных специалистов"

  vcdx_evolution:
    - "VCDX теперь фокусируется на VMware Cloud Foundation"
    - "Путь: VCP → VCAP → VCDX"
```

---

## WRITING GUIDELINES

### Терминология

```yaml
terminology:
  correct:
    - "гипервизор" (не "хайпервайзер")
    - "виртуальная машина, ВМ" (не "вирт")
    - "живая миграция, live-миграция" (не "лайв мигрейшн")
    - "программно-определяемый" (не "софтверно-дефайнед")
    - "гиперконвергентная инфраструктура" (не "HCI" в первом упоминании)
    - "импортозамещение" (контекст: замена иностранного ПО)

  abbreviations_expand:
    VM: "виртуальная машина"
    HCI: "гиперконвергентная инфраструктура"
    SDN: "программно-определяемая сеть"
    SDS: "программно-определяемое хранилище"
    SDDC: "программно-определяемый ЦОД"
    VDI: "инфраструктура виртуальных рабочих столов"
```

### Стиль написания

```yaml
style:
  tone:
    - "Профессиональный, технически грамотный"
    - "Практико-ориентированный"
    - "Без маркетинговых преувеличений"
    - "С конкретными примерами и цифрами"

  structure:
    - "Начинать с бизнес-проблемы"
    - "Объяснять технические концепции доступно"
    - "Давать практические рекомендации"
    - "Приводить реальные кейсы"

  avoid:
    - "Устаревшие данные о VMware (до Broadcom)"
    - "Реклама конкретных вендоров"
    - "Технический жаргон без объяснения"
    - "Преувеличение проблем или преимуществ"
```

### Экспертные формулировки

```yaml
expert_phrases:
  intro_good:
    - "По данным Gartner, 70% клиентов VMware к 2028 году мигрируют половину рабочих нагрузок на альтернативные платформы."
    - "С 1 января 2025 года использование иностранного ПО на объектах КИИ запрещено — это ускорило переход на российские платформы виртуализации."

  intro_bad:
    - "В современном мире виртуализация очень важна..."
    - "Все знают, что VMware — лидер рынка..."

  recommendations_good:
    - "Перед миграцией проведите инвентаризацию: определите критичные VM, оцените зависимости, рассчитайте требования к ресурсам."
    - "Для минимизации рисков используйте поэтапную миграцию: сначала dev/test, затем staging, и только потом production."

  recommendations_bad:
    - "Нужно просто перенести виртуальные машины"
    - "Выбирайте любую альтернативу VMware"
```

### Ключевые тезисы для статей

```yaml
key_messages:
  vmware_not_default:
    headline: "VMware больше не 'по умолчанию'"
    supporting_points:
      - "58% российских компаний в 2025 году ещё используют VMware"
      - "Мир вокруг них уже радикально изменился"
      - "'Отраслевой стандарт' в России — это уже не VMware"

  support_timeline:
    headline: "Таймер уже тикает"
    facts:
      - "vSphere 7.x: End of General Support — 2 октября 2025"
      - "vSphere 8.0: End of General Support — 11 октября 2027"
      - "Perpetual-лицензии больше не продаются"
      - "Подписки через VCF/VVF недоступны в РФ"

  regulatory_pressure:
    headline: "Регуляторика против VMware"
    facts:
      - "VMware не в реестре Минцифры"
      - "С 2026 года — ужесточение требований по виртуализации"
      - "Гипервизор — самое узкое место при аттестации ИСПДн"
      - "При инциденте сложно доказать 'разумные меры'"

  new_standard_criteria:
    headline: "Новый стандарт в России — это стек, который:"
    criteria:
      - "Официально продаётся и поддерживается в стране"
      - "Укладывается в регуляторные требования"
      - "Имеет понятную долгосрочную перспективу"

  vk_cloud_positioning:
    headline: "VK Cloud — логичный следующий шаг"
    differentiators:
      - "Российский вендор, который не уйдёт из-за санкций"
      - "8+ лет на рынке (с эпохи Mail.ru Cloud Solutions)"
      - "Архитектура под российскую регуляторику с самого начала"
      - "Локальная команда разработки и поддержки"

  migration_is_project:
    headline: "Миграция — управляемый проект, а не катастрофа"
    approach:
      - "Инвентаризация → Проектирование → dev/test → бизнес-сервисы → критичный прод"
      - "Чем раньше начать — тем спокойнее ближайшие годы"
      - "Планомерная эволюция вместо пожаротушения"
```

---

## TOPICS EXPERTISE

### Темы для статей

```yaml
vmware_changes:
  topics:
    - "Изменения лицензирования VMware после Broadcom"
    - "Что означает минимум 72 ядра для SMB"
    - "VCF 9.0 — что нового для enterprise"
    - "Конец бессрочных лицензий VMware — как адаптироваться"
  depth: deep

migration:
  topics:
    - "Миграция с VMware на Proxmox — пошаговое руководство"
    - "Миграция на российские платформы виртуализации"
    - "Инструменты миграции с VMware: сравнение"
    - "Стратегии миграции: lift-and-shift vs refactor"
  depth: deep

russian_virtualization:
  topics:
    - "Российские платформы виртуализации 2025: обзор рынка"
    - "zVirt vs vStack vs Базис — сравнение"
    - "Импортозамещение VMware: кейсы и опыт"
    - "КИИ и виртуализация: требования 2025"
    - "Выход из VMware-зависимости: почему сейчас критичное время"
  depth: deep

vk_cloud_migration:
  topics:
    - "Миграция с VMware во VK Cloud: пошаговое руководство"
    - "VK Cloud как альтернатива VMware: сравнение возможностей"
    - "Почему VK Cloud — логичный следующий шаг после VMware"
    - "ПДн и виртуализация: как VK Cloud решает проблему аттестации ИСПДн"
    - "Два сценария миграции: из облака провайдера и из собственного ЦОД"
  depth: deep

regulatory_compliance:
  topics:
    - "152-ФЗ и виртуализация: требования к гипервизору"
    - "Аттестация ИСПДн: почему гипервизор — узкое место"
    - "Ужесточение требований 2026: что меняется для виртуализации"
    - "VMware vs реестр Минцифры: юридические риски"
  depth: deep

alternatives:
  topics:
    - "Альтернативы VMware 2025: полное сравнение"
    - "Proxmox VE для enterprise: возможности и ограничения"
    - "Nutanix AHV как замена VMware"
    - "KubeVirt: виртуальные машины в Kubernetes"
  depth: medium

technology:
  topics:
    - "vSAN: архитектура и best practices"
    - "NSX-T: программно-определяемая сеть"
    - "Гиперконвергентная инфраструктура: выбор платформы"
    - "SDDC: концепция и реализация"
  depth: deep

career:
  topics:
    - "Сертификация VMware VCP в 2025"
    - "Карьера специалиста по виртуализации"
    - "Какие навыки нужны для работы с альтернативами VMware"
  depth: medium
```

---

## STATISTICS & FACTS

### Рыночная статистика

```yaml
market_stats:
  global:
    vmware_migration_plans: "56% планируют сократить использование VMware"
    alternatives_consideration: "98% рассматривают альтернативы"
    gartner_prediction: "70% мигрируют 50% нагрузок к 2028"

  russia:
    domestic_share: "60.2% (2024)"
    market_2025: "19 млрд рублей"
    market_2031: "51.4 млрд рублей"
    cagr: "17.9%"
    adoption: "30%+ используют российские системы"
    vmware_usage_2025: "58% российских компаний продолжают использовать VMware"
    source: "Исследование «Код Безопасности»"

  price_increases:
    average: "3-6x"
    europe_max: "до 1500%"
    att_example: "1050%"

  support_deadlines:
    vsphere_7x_eogs: "2 октября 2025"
    vsphere_8x_eogs: "11 октября 2027"
    vsphere_8x_tech_guidance: "До 2029 без фиксов"
```

### Технические факты

```yaml
technical_facts:
  vsan_performance: "До 150 000 IOPS на узел"
  vcf_licensing_min: "72 ядра (было 16)"
  proxmox_cost: "Бесплатно (AGPL v3)"
  vcp_certified: "100 000+ специалистов (VCP6-DCV)"
```

---

## SOURCES & REFERENCES

```yaml
sources:
  news:
    - name: "vm-guru.com"
      topics: ["VMware новости", "лицензирование", "обновления"]
      url: "https://vm-guru.com"

    - name: "Хабр"
      topics: ["Технические статьи", "миграция", "обзоры"]
      url: "https://habr.com"

    - name: "CNews"
      topics: ["Российский рынок", "импортозамещение"]
      url: "https://cnews.ru"

  analytics:
    - name: "Gartner"
      topics: ["Прогнозы рынка", "рекомендации"]

    - name: "iKS-Consulting"
      topics: ["Российский рынок виртуализации"]

    - name: "Anti-Malware.ru"
      topics: ["Обзоры российских решений"]

  official:
    - name: "VMware Blogs"
      url: "https://blogs.vmware.com"
      note: "Официальные анонсы End of Support, лицензирование"

    - name: "Proxmox"
      url: "https://proxmox.com"

    - name: "Nutanix"
      url: "https://nutanix.com"

    - name: "VK Cloud / VK Tech"
      url: "https://cloud.vk.com"
      note: "Российская облачная платформа"

  regulatory:
    - name: "Реестр российского ПО"
      url: "https://reestr.digital.gov.ru"
      note: "Требования к импортозамещению виртуализации с 2026"

    - name: "data-sec.ru"
      topics: ["152-ФЗ", "ФСТЭК", "ИСПДн"]
      note: "Регуляторика персональных данных"

    - name: "invgate.com"
      topics: ["VMware End of Support dates"]
      note: "Сроки окончания поддержки vSphere"

  research:
    - name: "Код Безопасности"
      topics: ["Исследование использования VMware в России"]
      stat: "58% российских компаний используют VMware (2025)"

    - name: "Блог компании Cortel"
      topics: ["VMware уход из России", "российская виртуализация"]
      note: "Анализ ситуации с VMware в РФ"

    - name: "Рувики"
      topics: ["VK Cloud история"]
      note: "История развития платформы"
```

---

## KEYWORDS & SEO

### Основные ключевые слова

```yaml
primary_keywords:
  - VMware
  - виртуализация
  - гипервизор
  - vSphere
  - ESXi
  - vCenter
  - альтернативы VMware
  - миграция VMware
  - импортозамещение виртуализации

secondary_keywords:
  - vSAN
  - NSX
  - VCF
  - VMware Cloud Foundation
  - Proxmox
  - Nutanix
  - KVM
  - гиперконвергентная инфраструктура
  - программно-определяемый ЦОД

russian_specific:
  - российская виртуализация
  - zVirt
  - vStack
  - Базис
  - импортозамещение VMware
  - КИИ виртуализация
  - VK Cloud
  - VK Tech
  - российское облако

regulatory_keywords:
  - 152-ФЗ
  - персональные данные
  - ИСПДн
  - аттестация ИСПДн
  - ФСТЭК
  - реестр Минцифры
  - реестр российского ПО
  - КИИ
  - критическая информационная инфраструктура

vmware_exit_keywords:
  - выход из VMware
  - VMware-зависимость
  - конец поддержки VMware
  - End of Support vSphere
  - миграция с VMware
  - альтернатива VMware в России
  - VMware уход из России

lsi_keywords:
  - виртуальная машина
  - серверная виртуализация
  - облачная инфраструктура
  - ЦОД
  - live-миграция
  - high availability
  - отказоустойчивость
  - кластеризация
  - гипервизор в России
  - облачная платформа
  - регуляторные требования
```
