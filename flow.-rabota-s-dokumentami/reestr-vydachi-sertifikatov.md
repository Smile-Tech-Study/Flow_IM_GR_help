# Реестр выдачи сертификатов

## Генерация реестра

:::info

Реестры выдачи сертификатов - таблица, где будет указано, что человеку, сдавшему экзамен успешно,  был выдан сертификат.

:::

Генерировать сертификаты могут **сотрудники экзаменационной площадки**. Для этого необходимо:

1. Отфильтровать экзамены по столбцу "Статус реестра сертификатов" в статусе "Генерация возможна".

![](<../.gitbook/assets/image (34).png>)

2. Перейти на страницу экзамена, для которого генерируется  реестр сертификатов.
3. Сгенерировать "Реестр выдачи сертификатов".

:::info

Кнопка "Сгенерировать" появляется после того, как будут сгенерированы и загружены все сертификаты для всех успешно сдавших экзамен граждан именно в этом экзамене. Пока загруженных сертификатов нет, статус будет "Генерация невозможна".

:::

![](<../.gitbook/assets/image (35).png>)

4. Скачать бланк.

![](<../.gitbook/assets/image (89).png>)

5. Собрать подписи. Отсканировать реестр и отправить его на проверку.

![](<../.gitbook/assets/image (91).png>)

## Проверка реестра выдачи сертификатов

Сотрудник центра тестирования:

1. открывает страницу со списком экзаменов и фильтрует экзамены по столбцу "Статус реестра сертификатов" по значению "Требуется проверка".

![](<../.gitbook/assets/image (36).png>)

2. Открывает экзамен и берёт реестр на проверку.

![](<../.gitbook/assets/image (37).png>)

3. Подтверждает (переход в статус Одобрен) или отклоняет (потребуется написать причину отклонения, чтобы сотрудник площадки мог исправить замечания и повторно направил реестр на проверку).

***

3. Реестр генерируется по следующему шаблону:

![](<../.gitbook/assets/Реестр выдачи сертификатов.xlsx" %}

***

## Статусы реестра выдачи сертификатов

* **Генерация невозможна** - в экзамене нет загруженных сканов сертификатов
* **Генерация возможна** -  загружены все сертификаты для всех успешно сдавших экзамен граждан в этом экзамене
* **На подписи** - сгенерирован реестр, сотрудник площадки скачал его и собирает подписи со сдающих при выдаче сертификата
* **Требуется проверка** - сотрудник площадки загрузил подписанный реестр выдачи сертификатов и ожидает проверки сотрудника центра тестирования.
* **На проверке** - сотрудник центра тестирования проверяет реестр.
* **Одобрен** - реестр одобрен.
* **Отклонен** - реестр отклонён, необходимо внести исправления и повторно отправить на проверку.

