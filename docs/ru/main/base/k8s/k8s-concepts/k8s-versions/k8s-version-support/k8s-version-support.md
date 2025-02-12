В Kubernetes aaS от VK Cloud новые версии преимущественно добавляются через 1 месяц после официального релиза.

В данный момент в Kubernetes aaS от VK Cloud доступны следующие версии Kubernetes:

- 1.23.6
- 1.22.6
- 1.21.4
- 1.20.4

При [создании нового кластера](../../../k8s-clusters/create-k8s) выбирайте последнюю доступную [версию Kubernetes](#k8s-versions-list). Мы настоятельно рекомендуем [обновлять кластер](../../../k8s-clusters/update-k8s) до последней доступной версии, при возможности.

Если кластер создан на [версии Kubernetes](#k8s-versions-list), которая более не поддерживается, то мы не можем гарантировать его корректную работу. Все возникающие проблемы с кластером должны решаться пользователем самостоятельно.

## Поддержка версий Kubernetes

Версии Kubernetes поддерживаются на протяжении 14 месяцев с даты релиза в Kubernetes aaS от VK Cloud.

Сообщение о прекращении поддержки версии Kubernetes будет разослано по электронной почте и в центре уведомлений личного кабинета за 30 дней до даты прекращения поддержки.

|Версия Kubernetes|Официальная дата релиза|Kubernetes aaS от VK релиз|Kubernetes aaS от VK завершение поддержки|
|------|------|------|-------|
|1.23.6|13 апреля 2022|15.08.2022|15.10.2023|
|1.22.6|19 января 2022|18.02.2022|18.04.2023|
|1.21.4|8 апреля 2021|12.10.2021|12.12.2022|
|1.20.4|8 декабря 2020|01.03.2021|01.05.2022|
|1.19.4|26 августа 2020|23.12.2020|23.02.2022|
|1.18.12|23 марта 2020|23.12.2020|23.02.2022|
|1.17.8|9 декабря 2019|09.08.2020|09.12.2021|

Историю изменений версий можно посмотреть [здесь](k8s-version-changelog).

## Поддержка функций сервиса в версиях Kubernetes

Новые функции по возможности добавляются во все версии, за исключением случаев несовместимости функции с версией Kubernetes.

| Наименование                             | 1.17.8 | 1.18.12 | 1.19.4 | 1.20.4 | 1.21.4 | 1.22.6 | 1.23.6 |
| ---------------------------------------- | ------ | ------- | ------ | ------ | ------ | ------ | ------ |
| Настройки масштабирования нод-группы     | +      | +       | +      | +      | +      | +      |+ |
| Инвалидация ключевой пары                | +      | +       | +      | +      | +      | +      |+ |
| Изменить размер диска Prometheus         | +      | +       | +      | +      | +      | +      |+ |
| Изменение типа виртуальной машины Master | +      | +       | +      | +      | +      | +      |+ |
| Обновить версию кластера                 | +      | +       | +      | +      | +      | +      |+ |
| Label & Taints                           | +      | +       | +      | +      | +      | +      |+ |
| Ноды кластера на AlmaLinux               | -      | -       | -      | -      | +      | +      |+ |
| Интеграция с VK CS Cloud IAM             | -      | -       | -      | -      | -      | -      | + |
