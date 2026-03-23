# SINGULAR.
### Industrial AI Platform

> Промышленная ИИ-платформа нового поколения для тяжёлой промышленности, нефтегаза и металлургии.

---

## Что мы строим

**Singular** — единая система которая объединяет разрозненные данные промышленного предприятия, предсказывает отказы оборудования и управляет автономными машинами.

90% телеметрии на производстве не анализируется. Незапланированная остановка стоит $125K в час. Singular решает обе проблемы.

---

## Продукты

| Модуль | Описание | Статус |
|--------|----------|--------|
| **Singular Predict** | Предиктивная аналитика. Предсказывает отказы оборудования за 2–4 недели до поломки | `active` |
| **Singular Vision** | Компьютерное зрение. HSE-контроль, детектирование утечек, мониторинг красных зон | `active` |
| **Singular Twin** | Цифровой двойник предприятия в реальном времени | `in development` |
| **Singular Forge** | Подготовка данных. Превращает неструктурированные данные в AI-ready датасеты | `active` |
| **Singular Drone** | Автономные дроны-инспекторы | `planned` |
| **Singular Exo** | Промышленные экзоскелеты | `planned` |

---

## Технологический стек

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

## Архитектура

```
┌─────────────────────────────────────────────────┐
│                  SINGULAR PLATFORM               │
├──────────────┬──────────────┬───────────────────┤
│    Predict   │    Vision    │       Twin        │
│  (Predictive │  (Computer   │  (Digital Twin)   │
│  Maintenance)│   Vision)    │                   │
├──────────────┴──────────────┴───────────────────┤
│                  Singular Forge                  │
│            (Data Fabric / AI-ready)              │
├─────────────────────────────────────────────────┤
│         ERP  ·  SCADA  ·  MES  ·  IoT           │
│              Industrial Infrastructure           │
└─────────────────────────────────────────────────┘
```

---

## Метрики

- **−30–50%** незапланированных простоев с Singular Predict
- **90 дней** до первых результатов с момента развёртывания
- **99%** точность детектирования утечек газа через ИК-камеры
- **×3** LTV клиента при переходе на полный стек платформы

---

## Репозитории

```
singular-platform/
├── singular-core       # Монорепо: ядро платформы и все модули
├── singular-sdk        # SDK для интеграции с внешними системами
├── singular-docs       # Документация и API Reference
└── singular-infra      # Инфраструктура: Helm charts, Terraform
```
---

<sub>© 2026 Singular. До Singular. После Singular.</sub>
