# Документация komnata — учебный проект

Практическая работа «Docs as Code: документация в репозитории».

| Папка или файл | Что это |
|---|---|
| `docs/` | Исходные страницы документации в Markdown |
| `mkdocs.yml` | Конфигурация генератора MkDocs: название, меню, тема |
| `product/` | Источник истины о продукте: вывод `--help` и конфигурация по умолчанию |
| `CHANGELOG.md` | Журнал изменений продукта |
| `styles/`, `.vale.ini` | Правила линтера прозы Vale |
| `.github/workflows/docs.yml` | Конвейер: сборка, проверки, публикация |
| `.github/pull_request_template.md` | Шаблон описания пул-реквеста |
| `compare/` | Папка для задания 5 |
| `REPORT.md` | Ваш отчёт по работе |

## Сборка на своём компьютере (необязательно)

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate    macOS, Linux: source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve          # сайт откроется по адресу http://127.0.0.1:8000
```
