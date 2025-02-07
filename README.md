## В этом блоке представлены мои решения задач по модулю **"Статистика"**.

Работа выполнена на Python с использованием Jupyter Notebook. 

<hr>

### [1 mini-project](https://github.com/ElenaAnalyst/stat_homeworks/blob/main/1_lesson.ipynb)
В этом мини-проекте мной были посчитаны несколько продуктовых метрик и показаны распределения, которые могут встретиться на практике.

#### Задачи: 
* Загрузить данные, проверить число наблюдений и столбцов, типы данных, наличие пропущенных значений, определить, какие уникальные значения встречаются
* Построить график распределения числа показов для каждой рекламы, прологарифмировав значения.
* Создать новую колонку c `CTR`. Посмотреть на описательные статистики и распределение.
* Проанализировать CTR с разбивкой по рекламной кампании.
* Посчитать стоимость за клик пользователя по объявлению `(CPC)`. Изучить полученные значения, используя меры центральной тенденции и меры изменчивости.
* Визуализировать CPC с разбивкой по полу пользователей, которым были показаны объявления.
* Посчитать `конверсию из клика в покупку`.

<hr>

### [2 mini-project](https://github.com/ElenaAnalyst/stat_homeworks/blob/main/1_lesson.ipynb)
Представьте, что вы работаете аналитиком в компании, которая занимается арендой велосипедов. Коллега из офиса в Лондоне прислал вам данные за два года: с 4 января 2015 по 3 января 2017. Вам предстоит изучить динамику числа аренд, наличие связи с погодными условиями и выходными, а также объяснить несколько аномалий на графике.

#### Задачи: 
* Загрузить данные, проверить число наблюдений и столбцов, наличие пропусков. Убедиться, что типы данных были прочитаны правильно. При необходимости – привести переменные к нужным типам.
* Построить график по числу поездок по дате и времени.
* Преобразовать данные и посчитать число поездок по дням. Визуализировать результат.
* Используя агрегированные данные по дням, посчитать скользящее среднее с окном 3. 
* Посчитать разницу между наблюдаемыми и значениями, подсчитанными с помощью скользящего среднего. Далее – найти стандартное отклонение.
* Определить границы 99% доверительного интервала, добавить данную информацию в датафрейм.
* Изучить аномально высокие значения. Найти причину данной аномалии.
* Изучите аномально низкие значения. Найти причину данной аномалии.

<hr>




### Реализация проекта:
* Провела предварительный анализ и предобработку данных.
* Использовала API для загрузки датасетов.
* Проанализировала поведение пользователей и работу доставки заказанных товаров. 
* Провела когортный анализ пользователей.
Построила RFM-сегментацию пользователей.
