# Плагины курса AI-Ковчег

Маркетплейс плагинов Claude Code для курса AI-Ковчег. Сейчас в нём один плагин — **marketing** для урока «Маркетинг: как превратить идею в понятное предложение».

## Установка

В Claude Code:

```text
/plugin marketplace add kkarpushin/kovcheg-marketing
/plugin install marketing@kovcheg
```

Из терминала то же самое: `claude plugin marketplace add kkarpushin/kovcheg-marketing`, затем `claude plugin install marketing@kovcheg`.

## Скиллы

| Команда | Что делает |
|---|---|
| `/marketing:client-dna` | ДНК клиента: глубинный анализ аудитории в 5 частях по собранным данным |
| `/marketing:hormozi-offer` | Оффер по методологии $100M Offers: агрессивная версия и адаптация |
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
offer/                  офферы
landing/                прототип лендинга
```

## Авторство

Методологии ДНК клиента, лестницы Ханта и оффера по Хормози в этих скиллах адаптировал Влад Ясько: исходные репозитории — kkarpushin/client-dna-v2, kkarpushin/hunt-ladder, kkarpushin/hormozi-offer. Лестница осознанности — Бен Хант. Оффер — по книге Алекса Хормози «$100M Offers».
