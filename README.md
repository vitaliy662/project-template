# 🏗️ Project Templates Repository

## 📦 Доступные шаблоны

| Ветка | Описание | Команда клонирования |
|-------|----------|---------------------|
| 🌱 **simple** | Базовый шаблон для быстрого старта (5–7 файлов) | `git clone --depth=1 https://github.com/vitaliy662/project-template.git -b simple` |
| 🚀 **complex** | Расширенный шаблон с CI/CD, тестами и структурой | `git clone --depth=1 https://github.com/vitaliy662/project-template.git -b complex` |

## 📦 Доступные шаблоны

| Ветка | Статус | Описание | Команда |
|-------|--------|----------|---------|
| 🌱 **simple** | ✅ Ready | Базовый шаблон для быстрого старта | `git clone --depth=1 https://github.com/vitaliy662/project-template.git -b simple` |
| 🚀 **complex** | ✅ Ready | Полноценный шаблон с CI/CD, тестами и структурой | `git clone --depth=1 https://github.com/vitaliy662/project-template.git -b complex` |

## 📁 Сравнение шаблонов

| Особенность | Simple | Complex |
|-------------|--------|---------|
| Базовая структура | ✅ | ✅ |
| CI/CD (GitHub Actions) | ❌ | ✅ |
| Тесты | ❌ | ✅ |
| Структура задач (tasks/) | ❌ | ✅ |
| Спецификации (docs/03-spec/) | ❌ | ✅ |
| Журнал решений (ADR) | ❌ | ✅ |
| Журнал работы (docs/06-log.md) | ❌ | ✅ |
| ROADMAP.md | ❌ | ✅ |

## 🛠️ Быстрый старт

```bash
# Вариант 1: Простой шаблон
git clone --depth=1 https://github.com/vitaliy662/project-template.git -b simple
cd project-template
# ... работайте с кодом

# Вариант 2: Расширенный шаблон
git clone --depth=1 https://github.com/vitaliy662/project-template.git -b complex
cd project-template
npm install  # если есть package.json
npm test
```

## 📁 Структура веток

- **`main`** — навигация по репозиторию
- **`simple`** — минималистичный шаблон (src/, docs/, tests/, assets/)
- **`complex`** — полноценный шаблон с CI/CD, структурой задач, спецификациями

## 📝 Лицензия

MIT © [vitaliy662](https://github.com/vitaliy662)
