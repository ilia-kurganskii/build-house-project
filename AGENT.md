# Инструкции для агента — документация стройки

Граф связанных заметок (Obsidian). При изменении документа — проверить связанные файлы и [[02-project-profile]].

## Структура

```
AGENT.md
docs/
  02-project-profile.md   — КАНОН проекта (читать первым)
  00-overview.md
  _graph.md
  milestones/M0–M15
```

**Obsidian:** vault = корень репозитория.

## Протокол при правке

1. [[02-project-profile]] — нет противоречий?
2. Frontmatter: `when_changed_review`, `concepts`
3. [[_graph]] — синхронизировать связанные файлы
4. Концепты — обновить везде, где используются

## Триггеры

| Изменил | Проверь |
|---------|---------|
| profile | overview, graph, M0, M1, M7, M10, M15 |
| starter 2×4 | M1–M5, M14, overview |
| L / 50 m² | M15, profile |
| односкат | M7, M8, M10, M15 |
| сваи starter | M1, M15 |

## Язык

Русский.
