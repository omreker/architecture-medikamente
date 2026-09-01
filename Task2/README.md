# Проектирование решения (Privacy by Design)

## Новые блоки архитектуры

- Privacy & Consent Service

- Data Tagging & Classification Service

- Policy Decision Point (OPA / Cerbos)

- Encryption & Key Management (Vault / KMS)

- Audit & Lineage Service

- Anonymization Pipeline

- API Gateway + Data Contracts

## Аналитический слой

- Raw / Restricted Zone (только с тегом restricted)

- Anonymization Pipeline

- Curated / Analytics Zone (Data Lake) - только обезличенные данные

- Контроль через CI/CD и мониторинг

## C4 Диаграммы

- [`C4_context_to_be.drawio`](C4_container_to_be.drawio)

- [`C4_container_to_be.drawio`](C4_context_to_be.drawio)
