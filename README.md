# Плагины курса AI-Ковчег

Маркетплейс плагинов Claude Code для курса AI-Ковчег. Сейчас в нём один плагин — **marketing** для урока «Маркетинг: как превратить идею в понятное предложение».

## Установка

В Claude Code — две команды, строго по одной: `/plugin` принимает только одну строку. Отправьте первую, дождитесь ответа, затем вторую.

```text
/plugin marketplace add kkarpushin/kovcheg-marketing
```

```text
/plugin install marketing@kovcheg
```

Из терминала то же самое: `claude plugin marketplace add kkarpushin/kovcheg-marketing`, затем `claude plugin install marketing@kovcheg`.

## Скиллы

| Команда | Что делает |
|---|---|
| `/marketing:client-dna` | ДНК клиента: глубинный анализ аудитории в 5 частях по собранным данным |
| `/marketing:hormozi-offer` | Оффер по методологии $100M Offers: агрессивная версия и адаптация |
| `/marketing:agora-offer` | Оффер новой возможности по формуле Agora: «чистое пиво» конкурентов, сгоревшие механизмы, уникальный механизм, «Это не X. Это Y», доказательства |
| `/marketing:hunt-ladder` | Лестница Бена Ханта: уровни осознанности и стратегия прогрева |
| `/marketing:audience-map` | Карта аудитории с портретами из ДНК клиента |

Claude включает скиллы и сам, по смыслу запроса.

## Папка проекта

```text
data/01-deep-research   отчёты Deep Research и ДНК бизнеса (урок 04)
data/02-telegram        выгрузки чатов и каналов
data/03-youtube         комментарии и расшифровки видео
data/04-custdev         анкеты и расшифровки интервью
dna/                    ДНК клиента и карта аудитории
offer/                  офферы: offer.md (Хормози), agora.md (новая возможность)
landing/                прототип лендинга
```
