# Prompt Contents

Коллекция промптов, агентов и плагинов для Claude Code — инструменты для создания SEO-статей, страниц мероприятий, пресс-релизов, обновления лендингов и технического контента.

**[Канал в Telegram](https://t.me/proitru)** — промты, новости ИИ, техноконтентское

---

## Содержание

- [Обзор плагинов](#обзор-плагинов)
- [Content Creation Suite](#content-creation-suite)
  - [Trend Researcher](#trend-researcher)
  - [Tech Writer](#tech-writer)
  - [Content Editor](#content-editor)
  - [SEO Publisher](#seo-publisher)
- [Landing Page Updater](#landing-page-updater)
- [SEO Content Creator](#seo-content-creator)
- [Event Page Wizard](#event-page-wizard)
- [Press Release Wizard](#press-release-wizard)
- [YAML-промты](#yaml-промты)
- [Доступные команды](#доступные-команды)
- [Структура репозитория](#структура-репозитория)

---

## Обзор плагинов

| Плагин | Назначение | Команда |
|--------|------------|---------|
| **Trend Researcher** | Исследование трендов и стратегия | `/trend-research` |
| **Tech Writer** | Написание технических статей | `/draft-article` |
| **Content Editor** | Фактчек и редактура | — |
| **SEO Publisher** | SEO и полный workflow | `/article-workflow` |
| **Landing Page Updater** | Обновление текстов лендингов | `/update-landing` |
| **SEO Content Creator** | SEO-оптимизированные статьи | `/seo-create-article` |
| **Event Page Wizard** | Страницы мероприятий | `/create-event` |
| **Press Release Wizard** | Профессиональные пресс-релизы | `/write-press-release` |

---

## Content Creation Suite

Профессиональная система создания контента для высокотехнологичных компаний. Разделена на 4 специализированных плагина, которые работают вместе через `/article-workflow`.

```
┌─────────────────────────────────────────────────────────────┐
│                     ARTICLE WORKFLOW                         │
├─────────────────────────────────────────────────────────────┤
│  1. trend-researcher  →  Исследование и стратегия           │
│  2. tech-writer       →  Написание черновика                │
│  3. content-editor    →  Фактчек и редактура                │
│  4. seo-publisher     →  SEO и подготовка к публикации      │
└─────────────────────────────────────────────────────────────┘
```

### Целевые издания

**Глобальные:** Forbes, Harvard Business Review, MIT Technology Review, TechCrunch, Wired, Ars Technica

**Российские:** Ведомости, РБК, Коммерсантъ, Хабр, VC.ru, CNews

---

### Trend Researcher

**Расположение:** `trend-researcher/`

Исследование технологических трендов и стратегическое планирование контента.

**Агент:** Tech Content Strategist

**Возможности:**
- Анализ технологических трендов и рыночных возможностей
- IMPACT-скоринг тем для приоритизации
- Конкурентный анализ контента
- Подготовка питчей для изданий
- Аудитория и pain points mapping

**Skill:** tech-trends-research — методология исследования, IMPACT framework

**Команда:** `/trend-research`

---

### Tech Writer

**Расположение:** `tech-writer/`

Профессиональное написание технического контента на русском и английском.

**Агент:** Tech Content Writer

**Форматы:**
- Opinion pieces и thought leadership (800-1,200 слов)
- Технические туториалы (1,500-2,500 слов)
- Case studies (1,200-2,000 слов)
- Trend analysis (1,000-1,800 слов)
- Whitepapers (2,500-5,000 слов)

**Skills:**
- enterprise-storytelling — корпоративное повествование
- technical-writing-standards — стандарты технического письма

**Команда:** `/draft-article`

---

### Content Editor

**Расположение:** `content-editor/`

Профессиональная редактура и проверка фактов.

**Агенты:**
- **Tech Fact-Checker** — проверка статистики, источников, кода, цитат
- **Content Editor** — структурное редактирование, улучшение текста

**Skills:**
- fact-checking-methodology — трёхуровневая модель верификации
- editorial-excellence — техники редактирования топовых изданий

**Иерархия источников:**

| Tier | Источники |
|------|-----------|
| Tier 1 | Официальная документация, peer-reviewed |
| Tier 2 | Аналитики (Gartner, IDC), официальные блоги |
| Tier 3 | Tech media, industry reports |
| Tier 4 | Блоги, форумы, соцсети |

---

### SEO Publisher

**Расположение:** `seo-publisher/`

SEO-оптимизация и подготовка к публикации. Оркестрирует полный workflow.

**Агент:** SEO Content Optimizer

**Возможности:**
- Оптимизация заголовков и A/B варианты
- Мета-описания и ключевые слова
- Улучшение читаемости
- Оптимизация для соцсетей
- Планирование дистрибуции

**Skill:** media-publishing-guidelines — гайдлайны для Forbes, TechCrunch, HBR, Habr, VC.ru

**Команда:** `/article-workflow` — полный цикл создания статьи

---

## Landing Page Updater

**Расположение:** `landing-updater/`

Интерактивный агент для обновления текстов лендингов с сохранением структуры и SEO-оптимизацией.

### Ключевой принцип

```
СОХРАНЯЕМ:                 ОБНОВЛЯЕМ:
- Количество блоков        - Формулировки
- Количество предложений   - Актуальность данных
- Иерархию H1->H2->текст   - SEO-оптимизацию
- Общий смысл              - Устаревшие термины
```

### Workflow из 7 этапов

```
┌──────────────────────────────────────────────────────┐
│  Этап 1: Получение текста (URL, файл, текст)        │
│  Этап 2: Разбор на блоки (автоматическая сегментация)│
│  Этап 3: SEO-параметры (ключи, title, description)  │
│  Этап 4: Референсы и указания                       │
│  Этап 5: Анализ и предложения по каждому блоку      │
│  Этап 6: Генерация обновлённого текста              │
│  Этап 7: Обратная связь и сохранение примера        │
└──────────────────────────────────────────────────────┘
```

### Типы блоков

| Тип | Описание |
|-----|----------|
| Hero | Главный заголовок H1, подзаголовок, CTA |
| Promo | Промо-баннер с акцией |
| Features | Преимущества продукта/сервиса |
| Solutions | Карточки решений/продуктов |
| Security | Безопасность, сертификаты, SLA |
| Trust | Клиенты, партнёры, логотипы |
| CTA | Call-to-Action блок |

---

## SEO Content Creator

**Расположение:** `seo-content-creator/`

Интерактивный агент для создания SEO-оптимизированных статей с пошаговым заполнением параметров.

### Wizard из 7 шагов

```
┌──────────────────────────────────────────┐
│  Step 1: Тема статьи          [ОБЯЗАТ.] │
│  Step 2: Ключевые слова       [ОБЯЗАТ.] │
│  Step 3: Режим генерации      [ОБЯЗАТ.] │
│  Step 4: Тон и аудитория      [ОБЯЗАТ.] │
│  Step 5: Структура            [ОПЦИОН.] │
│  Step 6: Доп. настройки       [ОПЦИОН.] │
│  Step 7: Подтверждение                  │
└──────────────────────────────────────────┘
```

### Режимы генерации

| Режим | Описание |
|-------|----------|
| `balanced` | Баланс между SEO и читаемостью |
| `deep_expert` | Технический экспертный контент |
| `light` | Упрощённый контент для широкой аудитории |
| `strict_seo` | Максимальная SEO-оптимизация |
| `brand_heavy` | Акцент на бренд |

---

## Event Page Wizard

**Расположение:** `event-page-wizard/`

Интерактивный агент для создания страниц мероприятий. Поддерживает вебинары, конференции, митапы, воркшопы, хакатоны и демо-дни.

### Wizard из 10 шагов

```
┌──────────────────────────────────────────────────────────┐
│  Step 1:  Тип мероприятия                     [ОБЯЗАТ.] │
│  Step 2:  Название                            [ОБЯЗАТ.] │
│  Step 3:  Дата и время                        [ОБЯЗАТ.] │
│  Step 4:  Формат и место                      [ОБЯЗАТ.] │
│  Step 5:  Описание                            [ОБЯЗАТ.] │
│  Step 6:  Программа                           [ОПЦИОН.] │
│  Step 7:  Спикеры                             [ОБЯЗАТ.] │
│  Step 8:  Целевая аудитория                   [ОПЦИОН.] │
│  Step 9:  Партнёры                            [ОПЦИОН.] │
│  Step 10: Дополнительно                       [ОПЦИОН.] │
└──────────────────────────────────────────────────────────┘
```

### Типы мероприятий

| Тип | Описание | Формат |
|-----|----------|--------|
| Вебинар | Онлайн-трансляция | online |
| Конференция | Масштабное мероприятие | hybrid |
| Митап | Неформальная встреча | offline |
| Воркшоп | Практическое занятие | offline |
| Хакатон | Соревнование разработчиков | hybrid |
| Демо-день | Презентация проектов | hybrid |

---

## Press Release Wizard

**Расположение:** `press-release-wizard/`

Интерактивный агент для написания пресс-релизов профессионального качества.

### Wizard из 10 шагов

```
┌─────────────────────────────────────────────────────────┐
│  ШАГ 1:  Приём материалов                              │
│  ШАГ 2:  Анализ материалов                             │
│  ШАГ 3:  Исследование рынка              [ОПЦИОН.]    │
│  ШАГ 4:  Уточняющие вопросы                            │
│  ШАГ 5:  Варианты заголовков (3 варианта)              │
│  ШАГ 6:  Варианты лидов + описание продукта            │
│  ШАГ 7:  Генерация основного текста                    │
│  ШАГ 8:  Подвал релиза (бойлерплейт)                   │
│  ШАГ 9:  Сборка и валидация                            │
│  ШАГ 10: Доработка                                     │
└─────────────────────────────────────────────────────────┘
```

### Типы пресс-релизов

| Тип | Описание |
|-----|----------|
| Запуск продукта | Новый сервис или платформа |
| Партнёрство | Совместный запуск с партнёром |
| Линейка | Несколько связанных продуктов |
| Обновление | Новая версия существующего продукта |

---

## YAML-промты

**Расположение:** `prompts/`

Standalone промты для использования в любых LLM без Claude Code.

| Файл | Описание |
|------|----------|
| `prompt_seo_1_analyze_and_build_params.yaml` | Аналитик параметров для SEO-статей |
| `prompt_seo_2_generate_article.yaml` | Генератор статей |
| `prompt_seo_3_infostyle_transformer_2_0.yaml` | Инфостайл-трансформер для лендингов |

---

## Доступные команды

| Команда | Плагин | Описание |
|---------|--------|----------|
| `/article-workflow` | seo-publisher | Полный workflow создания статьи |
| `/trend-research` | trend-researcher | Исследование трендов |
| `/draft-article` | tech-writer | Создание черновика статьи |
| `/seo-create-article` | seo-content-creator | SEO wizard |
| `/create-event` | event-page-wizard | Создание страницы мероприятия |
| `/write-press-release` | press-release-wizard | Написание пресс-релиза |
| `/update-landing` | landing-updater | Обновление лендинга |

---

## Структура репозитория

```
prompt-contents/
├── .claude/
│   └── commands/                        # Глобальные slash-команды
│       ├── article-workflow.md
│       ├── create-event.md
│       ├── draft-article.md
│       ├── seo-create-article.md
│       ├── trend-research.md
│       └── write-press-release.md
│
├── trend-researcher/                    # Исследование трендов
│   ├── .claude/
│   │   ├── agents/tech-content-strategist.md
│   │   ├── commands/trend-research.md
│   │   └── skills/
│   │       └── tech-trends-research/SKILL.md
│   └── README.md
│
├── tech-writer/                         # Написание статей
│   ├── .claude/
│   │   ├── agents/tech-content-writer.md
│   │   ├── commands/draft-article.md
│   │   └── skills/
│   │       ├── enterprise-storytelling/SKILL.md
│   │       └── technical-writing-standards/SKILL.md
│   └── README.md
│
├── content-editor/                      # Фактчек и редактура
│   ├── .claude/
│   │   ├── agents/
│   │   │   ├── tech-fact-checker.md
│   │   │   └── content-editor.md
│   │   └── skills/
│   │       ├── fact-checking-methodology/SKILL.md
│   │       └── editorial-excellence/SKILL.md
│   └── README.md
│
├── seo-publisher/                       # SEO и публикация
│   ├── .claude/
│   │   ├── agents/seo-content-optimizer.md
│   │   ├── commands/article-workflow.md
│   │   └── skills/
│   │       └── media-publishing-guidelines/SKILL.md
│   └── README.md
│
├── landing-updater/                     # Landing Page Updater
│   ├── .claude/
│   │   ├── agents/landing-updater-wizard.md
│   │   ├── commands/update-landing.md
│   │   └── skills/landing-knowledge.md
│   └── README.md
│
├── seo-content-creator/                 # SEO wizard
│   ├── .claude/
│   │   ├── agents/seo-wizard.md
│   │   ├── commands/create-article.md
│   │   └── skills/seo-knowledge.md
│   └── README.md
│
├── event-page-wizard/                   # Event wizard
│   ├── .claude/
│   │   ├── agents/event-wizard.md
│   │   ├── commands/create-event.md
│   │   └── skills/event-templates.md
│   ├── examples/
│   │   ├── webinar-simple.md
│   │   └── conference-full.md
│   └── README.md
│
├── press-release-wizard/                # Press Release wizard
│   ├── .claude/
│   │   ├── agents/press-release-wizard.md
│   │   ├── commands/write-press-release.md
│   │   └── skills/press-release-knowledge.md
│   ├── examples/
│   │   ├── product-launch.md
│   │   ├── partnership.md
│   │   ├── product-line.md
│   │   └── product-update.md
│   ├── prompts/
│   │   └── press-release-universal-prompt.md
│   └── README.md
│
├── prompts/                             # YAML-промты
│   ├── prompt_seo_1_analyze_and_build_params.yaml
│   ├── prompt_seo_2_generate_article.yaml
│   └── prompt_seo_3_infostyle_transformer_2_0.yaml
│
├── articles/                            # Сгенерированные статьи (примеры)
│
├── README.md
└── CLAUDE.md
```

---

## Лицензия

MIT

---

**Автор:** [levashove](https://github.com/levashove)
