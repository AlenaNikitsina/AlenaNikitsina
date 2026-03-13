<h1 align="center">Привет, я <a href="https://daniilshat.ru/" target="_blank">Алена</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Data analyst | Product analyst</h3>

____
 В этом репозитории собраны мои проекты по анализу данных, A/B-тестированию, ETL-разработке и созданию систем мониторинга. Все проекты выполнены с использованием современных инструментов и подходов: Python, ClickHouse, Airflow, статистические методы и байесовское моделирование.

---

## 📊 Обзор проектов

| Проект | Описание | Ключевые технологии | Основные результаты |
|--------|----------|---------------------|---------------------|
| **[A/B Testing Analytics Framework](https://github.com/yourusername/ab-testing-framework)** | Комплексный фреймворк для анализа A/B-тестов, включающий валидацию системы сплитования (AA-тест), анализ результатов эксперимента и применение линеаризации метрик. | Python, ClickHouse, pandas, scipy, numpy, matplotlib, seaborn | ✅ AA-тест подтвердил корректность сплитования (5% ложных срабатываний)<br>✅ Выявлено, что новый алгоритм хуже контроля (CTR ниже)<br>✅ Линеаризация повысила чувствительность t-теста (p-value уменьшилось с 0.68 до 2.98e-9) |
| **[Monte Carlo Power Analysis for A/B Test](https://github.com/yourusername/monte-carlo-power-analysis)** | Оценка статистической мощности A/B-теста с помощью симуляций Монте-Карло на основе реальных данных из ClickHouse. Моделирование эффекта ML-алгоритма и анализ влияния параметров эксперимента. | Python, ClickHouse, pandas, numpy, scipy, matplotlib, seaborn | 📊 Мощность теста: 41.7% (1 неделя, порог 50)<br>📊 Мощность теста: 63.5% (2 недели, порог 30 + фильтрация)<br>💡 Рекомендация: доработать алгоритм для достижения 80% |
| **[Flashmob Effectiveness Analysis with CausalImpact](https://github.com/AlenaNikitsina/Prediction_of_metrics.git)** | Оценка эффективности флэшмоба в ленте новостей с помощью байесовского метода CausalImpact. Анализ краткосрочных и долгосрочных эффектов на ключевые метрики. | Python, ClickHouse, pandas, causalimpact, matplotlib, seaborn | 📈 Просмотры: +180% (p=0.00)<br>📈 Уникальные посты: +40% (p=0.00)<br>📈 CTR: +3.3% (p=0.00)<br>📉 DAU: +7% (p=0.15, не значимо)<br>💡 Долгосрочного эффекта не обнаружено |
| **[ETL-пакет для агрегации пользовательских метрик](https://github.com/yourusername/parallel-user-metrics-pipeline)** | ETL-пакет в Apache Airflow для ежедневной агрегации пользовательских метрик из двух источников (`feed_actions` и `message_actions`) с записью в ClickHouse. Параллельная обработка и расчет срезов по полу, возрасту и ОС. | Apache Airflow, Python, ClickHouse, pandas, clickhouse-driver | 🔄 Ежедневный автоматический расчет метрик<br>📊 Финальная таблица с 9 метриками в разрезе 3 измерений<br>⚡ Параллельная обработка сокращает время выполнения DAG |
| **[Telegram Analytics Reports (Lenta & App)](https://github.com/yourusername/telegram-analytics-reports)** | Автоматическая отправка ежедневной аналитической сводки в Telegram. Два отчета: по ленте новостей и сводный по всему приложению, включая текстовые данные и графики за 7 дней. | Python, Airflow, ClickHouse, matplotlib, python-telegram-bot, pandas | 🤖 Ежедневная доставка отчетов в 11:00<br>📊 Отчет по ленте: DAU, просмотры, лайки, CTR<br>📱 Сводный отчет: 15+ метрик + 2 графика<br>✅ Полная автоматизация рутинной отчетности |
| **[Real-time Anomaly Detection Alerts](https://github.com/yourusername/anomaly-detection-alerts)** | Система мониторинга ключевых метрик приложения с проверкой каждые 15 минут. Обнаружение аномалий методом межквартильного размаха (IQR) и отправка алертов в Telegram с графиками и ссылками на дашборды. | Python, Airflow, ClickHouse, pandas, seaborn, matplotlib, python-telegram-bot | 🚨 Обнаружение аномалий за 15 минут<br>📊 График с историей и границами IQR в каждом алерте<br>🔗 Прямые ссылки на дашборды Superset<br>⚙️ Масштабируемая архитектура (легко добавлять новые метрики) |

---

## 🛠 Общий стек технологий

| Категория | Технологии |
|-----------|------------|
| **Языки программирования** | Python 3.8+ |
| **Базы данных** | ClickHouse, PostgreSQL |
| **Оркестрация** | Apache Airflow |
| **Анализ данных** | pandas, numpy, scipy.stats |
| **Статистика и A/B-тесты** | t-test, Mann-Whitney, бутстреп, CausalImpact, линеаризация, анализ мощности |
| **Визуализация** | matplotlib, seaborn |
| **Мониторинг и алерты** | IQR, Telegram Bot API |
| **ETL** | pandahouse, clickhouse-driver |

---

## 📫 Контакты

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Alena_Nikitsina)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:al.l.nikitsina@gmail.com)

- **Email:** al.l.nikitsina@gmail.com
- **Telegram:** @Alena_Nikitsina

____
🛠️ Языки и инструменты:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)

____




<!--
**AlenaNikitsina/AlenaNikitsina** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
