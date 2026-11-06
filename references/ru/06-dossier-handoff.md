# Полное досье и передача в AI coding agent — опционально

Загружать **только** по запросу подробного досье, передачи в разработку или технического проекта.

1. Executive brief: задача, границы, пользователи, кто одобряет решения.
2. Evidence ledger: факты со ссылками, выводы, гипотезы, неизвестные и временные ограничения данных.
3. Три открытия: каждое влияет на выбор или измерение результата.
4. Семь уровней: статус, сущности, гарантии, зависимости, опасные допущения, тест и ответственный.
5. Бизнес-процесс и модель данных: события, состояния, контракты, проверенность интеграций, границы доверия.
6. Архитектура: diagram, decision engines, agent harness лишь если нужен, наблюдаемость и восстановление.
7. Три golden cases: вход, ожидаемое поведение, критерий провала, покрытие.
8. Delivery: Discovery → Prototype → Working MVP → Production → Scale; критерии переходов.
9. Время и TCO: деньги/часы/ставки/12 месяцев и чувствительность; верификация цены.
10. Build/Buy/Hybrid/Don't Build Yet: противоположное решение, эксперимент для пересмотра и первая проверка.

Передача в кодирующий агент:

```text
PROJECT_CONTEXT:
CONFIRMED_REQUIREMENTS:
HYPOTHESES_AND_UNVERIFIED_ASSUMPTIONS:
DOMAIN_MODEL_AND_INVARIANTS:
DATA_SOURCES_AND_CONTRACT_STATUS:
ARCHITECTURE_AND_TRUST_BOUNDARIES:
AI_AGENTS_SKILLS_HARNESS_IF_NEEDED:
GOLDEN_TESTS_AND_EVALUATION:
DELIVERY_BLOCKERS_AND_GATES:
COSTS_AND_TCO_ASSUMPTIONS:
BUILD_BUY_AND_REVERSAL_TRIGGER:
IMPLEMENTATION_RULES: verify first; no unapproved production mutations
```

Незаполненные поля не выдавать за установленные требования. Статус доступа к реальным данным и API должен быть указан явно.
