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

  trends:
    - "Снижение зависимости от зарубежных решений"
    - "Рост спроса на AI/ML инфраструктуру"
    - "Повышение требований к безопасности"
    - "Импортозамещение"
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

  price_increases:
    average: "3-6x"
    europe_max: "до 1500%"
    att_example: "1050%"
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

    - name: "Proxmox"
      url: "https://proxmox.com"

    - name: "Nutanix"
      url: "https://nutanix.com"
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

lsi_keywords:
  - виртуальная машина
  - серверная виртуализация
  - облачная инфраструктура
  - ЦОД
  - live-миграция
  - high availability
  - отказоустойчивость
  - кластеризация
```
