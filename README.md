# My-portfolio

Привет! Меня зовут Алина, я начинающий аналитик данных. Моя сфера интересов - анализ данных, системный и бизнес анализ. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

<b>Навыки и технологии</b>
<br>
- Инструменты анализа данных: SQL, Excel, Word, CSV
- Системы управления базами данных: MySQL, PostgreSQL
- Средства визуализации данных: PowerBi
- Управление проектами: Miro, Jira, Trello
</br>

<b>Проекты</b>
<br>

<b>Проект 1: Калькулятор юнит-экономики онлайн-школы </b>

Что нужно было сделать: 

Задача №1 Настроить в калькуляторе учет корректировок планов маркетинга.
<br>
Задача №2 Пересчитать план найма преподавателей.
<br>
Как решала: 
1) Добавила в список параметров калькулятора показатель "Поправочный коэфициент на привлечение"																			
2) Установила значение этого показателя по умолчанию как 100% и добавила возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение"																			
3) Настроила динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов должно быть больше на 20%								
4) Просчитала сценарий, при котором планы маркетинга будут увеличены на 12% 	
5) Добавила в калькулятор Найма преподавателей возможность изменять входных параметры: Пропускную способность П и Retention П - с помощью дополнительного столбца с процентными изменениями.
6) Сделала поправку в расчёте общей пропускной способности - изменила формулу так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром
7) Обновила прогнозное количество уроков, добавив новые значения из Задачи 1 (полученные после поправки на планы маркетинга)
8) Просчитала сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента
9) С помощью Поиска решений составила новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей

Ссылка на проект [Проект1](https://github.com/Alina-Kurchenko/My-porfolio/tree/dd34d258cfe22d868f7632f5ee210b4731a95e77/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%821)

Выводы (итоги): 

Итог №1 Обновленный лист с калькулятором + новое расчётное количество студентов на 04.2022
<br>
Итог №2 Обновлённый план по найму с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022
</br>
<br>

<b>Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</b>

Что нужно было сделать: 

Задача №1 На основе анализа предоставленных данных ответить на вопрос, какая динамика пользовательской активности на платформе, опираясь на все рассчитанные метрики. Оформить выводы.
<br>
Задача №2.Создать Excel - файл, в котором будут автоматически рассчитываться перечисленные метрики, то есть калькулятор юнит-экономики.
<br>
Как решала: 
<br/>
1. Рассчитала количество подписок в каждый месяц       
2. Рассчитала количествово просмотров в каждый месяц  
3. Рассчитала количество уникальных просматривающих пользователей в каждый месяц
4. Найдена дата первого просмотра для каждого юзера
5. Найдено количество первых просмотров для пользователя в каждый месяц
6. Найдено среднее количество просмотров на одного юзера в каждом месяце
<br>
Далее приступила к сборке калькулятора юнит-экономики, для этого проделала следующие шаги:
<br>
1. Нашла количество повторных оплат в каждом месяце
<br>
2. Рассчитала Retention для каждого месяца
<br>
3. Рассчитала среднее геометрическое Retention   
<br> 
4. Рассчитала лайфтайм    
<br>   
5. Рассчитала LTR 
<br>
6. Рассчитала CAC 
<br>   
7. Нашла маржинальность
<br>
Настроив калькулятор юнит-экономики приступила к визуализации данных:
<br/>
1. Построила график 1: количество пользователей и интенсивность просмотров
<br>
2. Построила график 2: пользовательский Retention      
<br>
3. Построила график 3: распределение просмотров по суточным часам (0-23) в разрезе будние-выходные 
<br>     
4. Построила график 4: распределение просмотров по тайтлам

Ссылка на проект [Проект 2](https://github.com/Alina-Kurchenko/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%202)

Выводы (итоги):

Итог №1 Настроен калькулятор юнит-экономики продукта, представляющий собой автоматизированную систему для быстрого принятия решений. 
<br>
Итог №2 Решены задачи, связанные с визуализацией результатов анализа данных
</br>
<br>


<b>Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</b>

Что нужно было сделать:
<br>
Задача №1 Построить распределение выплаченных клиентами денег (amt_payment) по месяцам поля date_purchase.
<br>
Задача №2. Дополнить запрос так, чтобы получилось три разных скользящих средних (по сумме денег по месяцам):
 - MA(3) — скользящее среднее, принимающее текущее значение и два предыдущих.
 - MA(7) — скользящее среднее, принимающее текущее значение и шесть предыдущих.
 - MA_2side(5) — двустороннее скользящее среднее, принимающее текущее значение, два предыдущих и два следующих.

Ссылка на проект [Проект 3](https://github.com/Alina-Kurchenko/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%203)

Выводы (итоги): 

Итог №1 Построила распределение выплаченных клиентами денег (amt_payment) по месяцам поля date_purchase
Итог №2 Дополнила запрос так, чтобы получилось три разных скользящих средних (по сумме денег по месяцам):
 - MA(3) — скользящее среднее, принимающее текущее значение и два предыдущих.
 - MA(7) — скользящее среднее, принимающее текущее значение и шесть предыдущих.
 - MA_2side(5) — двустороннее скользящее среднее, принимающее текущее значение, два предыдущих и два следующих.
</br>
<br>

<b>Проект 4: Построение витрины для модели машинного обучения в банке</b>

Что нужно было сделать: 
<br>
задача №1. Специалисты по машинному обучению попросили вас составить витрину для их модели.
<br>
Как решала: 
<br>
Взяла таблицу skybank.late_collection_clients и написала скрипт, который сделает витрину со следующими полями:
<br>
Внутренний идентификатор клиента — поле id_client.
<br>
Название города — поле name_city из таблицы skybank.region_dict.
<br>
Числовой признак, который принимает значение 1 для мужчин и 0 для женщин — новое поле nflag_gender на основании поля gender.
<br>
Возраст — поле age.
<br>
Числовая переменная, которая показывает, в первый ли раз клиент обратился к нам за кредитом, — поле first_time.
<br>
Числовой признак, который принимает значение 1 при наличии мобильного телефона и 0 при его отсутствии — новое поле nflag_cellphone на основании поля cellphone.
<br>
Числовая переменная, которая показывает, активен ли клиент, — поле is_active;
<br>
Номер клиентского сегмента — поле cl_segm.
<br>
Размер выданного кредита — поле amt_loan.
<br>
Дата выдачи кредита — поле date_loan. (Привела к формату даты).
<br>
Тип выданного кредита — поле credit_type.
<br>
<b>На основании вышеперечисленных показателей, рассчитываем:</b>
<br>
Суммарный объем кредитов, выданных в этом городе.
<br>
Доля данного кредита среди всех кредитов, выданных в этом городе.
<br>
Суммарный объем кредитов, выданных в рамках указанного типа кредита.
<br>
Доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита.
<br>
Суммарный объем кредитов, выданных в рамках указанного типа кредита и города.
<br>
Доля данного кредита среди всех кредитов, выданных в рамках указанного типа кредита и города.
<br>
Количество кредитов, выданных в этом городе.
<br>
Количество кредитов, выданных в рамках указанного типа кредита.
<br>
Количество кредитов, выданных в рамках указанного типа кредита и города.
<br>
Ссылка на проект [Проект 4](https://github.com/Alina-Kurchenko/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%204)

Выводы (итоги):
Построила витрину для модели машинного обучения в банке
</br>
<br>

<b>Проект 5: Моделирование изменения балансов студентов</b>
<br>
Что нужно было сделать:
<br>
Задача №1 Смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента. 
<br>
Задача №2. Создать таблицу, где будут балансы каждого студента за каждый день.
<br>
Как решала:
<br>
Собрала таблицу, в которой для каждого студента хранится его первая дата успешной (со статусом success) транзакции (из таблицы payments).
<br>
Собрала таблицу, которая хранит в себе все дни 2016 года.
<br>
Собрала таблицу со списком успешных транзакций из таблицы payments.
<br>
Создала СТЕ для всех запросов из предыдущих шагов
<br>    
Создала СТЕ под названием all_dates_by_user, в котором объединила all_dates и first_payments, в нем хранятся все даты жизни студента после того, как произошла его первая транзакция.
<br>
Нашла изменения балансов из-за прохождения уроков. 
<br>
Нашла баланс студентов, который сформирован только транзакциями. Для этого объединила all_dates_by_userи payments_by_datesтак, чтобы совпадали даты и user_id .
<br>
По аналогии с уже проделанным шагом для оплат создала CTE classes_by_dates_dates_cumsum для хранения кумулятивной суммы количества пройденных уроков. 
<br>
Создала CTE balances с вычисленными балансами каждого студента. Для этого объединила таблицы payments_by_dates_cumsum и classes_by_dates_dates_cumsum так, чтобы совпадали даты и user_id. 
<br>
Выбрала топ-1000 строк из CTE balances с сортировкой по user_id и dt. Провела анализ изменения балансов студентов.Возникли вопросы к владельцам таблицы о корректности отображения данных.
<br>
Посмотрела, как менялось общее количество уроков на балансах студентов. Для этого просуммировала поля transaction_balance_change, transaction_balance_change_cs, classes, classes_cs, balance из CTE balances с группировкой и сортировкой по dt.
<br>
Создала визуализацию (линейную диаграмму) итогового результата. 
<br>
Ссылка на проект [Проект 5](https://github.com/Alina-Kurchenko/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%205)
<br>
Выводы (итоги):
<br>
Итог №1 В результате получился запрос, который собирает данные о балансах студентов за каждый прожитый ими день.
<br>
Итог №2 Построена визуализация данных и исходя из данных визуализации можно сделать вывод что покупка уроков в январе,  середине марта и в августе снижается, что вероятнее всего обусловлено праздничными днями в начале года и отпусками в летний период, осенью же показатель покупки уроков и списание уроков взрастает – следовательно осенью пользователи более активно учатся.
</br>
