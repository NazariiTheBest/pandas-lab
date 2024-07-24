Програмний проєкт (лабораторна робота) № 6
Обробка та візуалізація даних
Задача	1
Інше	1
Принципи академічної доброчесності (дуже важливо!)	1
Організаційні моменти	1
Звітність	2
Перевірка програмних проєктів	2
Задача
У файлі weather.csv знаходиться архів погодних даних.

Завдання має виконуватись у Jupyter Notebook (має бути один блокнот). Уся обробка даних має виконуватись виключно засобами pandas.
0. На початку блокноту має зазначатися виконавець, група та варіант, а також версії використаних бібліотек pandas, matplotlib і самого python.
1. Для періоду P = номер_варіанту%12 +1 (місяць) побудувати лінійні графіки зміни денної температури, нічної температури, хмарності та сили вітру по днях. Графіки укласти на один рисунок (але не в один графік).
2. Для періоду P побудувати бульбашковий (scatter) графік денної температури, діаметр “бульбашки” має залежати від кількості опадів. Якщо опадів не було, то підібрати якесь невелике значення, щоб була просто помітна точка.
3. Знайти середнє по місяцях відхилення нічної температури від денної.
4. Знайти всі дні, коли фіксувалась найбільша розбіжність між денною та нічною температурами, та вивести для них усю наявну інформацію.
5. У періоді P знайти 4 найбільш вітрених дні та вивести для них усю наявну інформацію.
6. Знайти скільки в кожному місяці було днів з опадами. Побудувати кругову діаграму.
7. Якщо хмарність більша 70%, то вважатимемо день хмарним. Якщо хмарність менша 35%, вважатимемо день сонячним. У решті випадків вважаємо, що в той день була мінлива хмарність. Знайти кількість днів кожного типу на місяць та побудувати стовпчикову діаграму з накопиченням.
8. Знайти всі місяці, в яких сонячних днів було більше, ніж днів з опадами.
9. Побудувати гістограму відхилення нічної температури від денної.

Нефункціональні вимоги
1. Робота має виконуватись самостійно.
2. Використовувані в програмі імена є змістовними, їх призначення зрозуміле з їх назви. Довгих імен слід уникати.
3. Коментарі дуже не заохочуються. Див. вище та нижче.
Принципи академічної доброчесності (дуже важливо!)
Студент вільно орієнтується в коді лабораторної роботи, яку він здає, розуміє усі використані синтаксичні елементи мови та бібліотечні засоби, зміст та призначення частин коду, вміє самостійно запустити програму на виконання, здатен самостійно внести локальні виправлення в код. У коді відсутні коментарі, що перекладають зміст інструкцій на природні мови. Наявність у довільних клітинах пояснень щодо того, що виконує код, прирівнюється до порушення академічної доброчесності, причому до такого, що спростоване бути не може.
Принципи академічної доброчесності передбачають, що ані брати чужий код, ані давати комусь свій не можна. Сумісна розробка також заборонена.
Організаційні моменти
Не пізніше 08 травня (для групи К12) та 29 травня (для груп К10, К11) 2024 року на адресу LabAssignment2@i.ua (далі «адреса для лабораторних робіт») та викладачу, що веде лабораторні заняття, має надійти лист з повним комплектом файлів та посилань, що стосуються програмного проєкту. У темі листа зазначено, що це лабораторна робота про pandas та номер варіанту, у форматі pandas, <номер варіанту>. Наприклад, pandas, 66
У самому листі зазначено виконавця та середовище, що використовувалося для виконання програмного проєкту. Один лист – один програмний проєкт, повністю. 
У листі мають бути наявні:
1) вкладення №1: блокнот з виконаним завданням; на початку має бути зазначений виконавець, варіант та група;
2) вкладення №2: pdf-звіт, отриманий конвертуванням блокноту.

Очний захист (обов’язковий для всіх): останнiй тиждень теоретичного навчання в семестрi. За погодженням можна ранiше.
Перевірка програмних проєктів
Програмний проєкт передбачає захист в очній формі та офлайн. Pdf-звіт також є невід’ємною частиною захисту програмного проєкту. За його відсутності позитивна кількість балів виставлена бути не може.  
Захист лабораторної роботи вважається неуспішним, якщо під час захисту виявляється, що студент не до кінця розуміє код або погано в ньому орієнтується чи не розуміє використані синтаксичні елементи мови, зміст та призначення частин коду, а також якщо захист не відбувся з ініціативи студента.
У випадку проведення захисту лабораторна робота може бути позитивно оцінена тільки у випадку, коли студент/студентка дав/дала правильні відповіді на всі запитання щодо структури зданого коду, змісту та призначення його елементів, використаних алгоритмів, а також вільно орієнтується у зданому коді та здатен/здатна правильно внести невеликі модифікації.
Оцінка за програмні проєкти, що були здані на перевірку невчасно, але не пізніше ніж за повний робочий тиждень до кінця теоретичного навчання в семестрі, знижується на 20%. Програмні проєкти, що надійшли на перевірку пізніше, перевіряються на офіційному перескладанні дисципліни (якщо воно буде призначене студенту), при цьому оцінка не може складати більше 60% від максимально можливої.
Згідно правил Університету, оцінки, що менше 9 балів, до загальної суми семестрових балів не додаються.

Якщо:
відсутній блокнот,
або він не може виконатись без помилок, якщо виконувати його від початку до кінця (за умови, що файл з даними розташовується в одній папці з блокнотом),
або відсутній pdf-звіт,
або pdf-звіт не відображає з чистого аркушу виконаний блокнот;
або не відбувся захист,
або хоча б одна версія порушує принципи академічної доброчесності,
або лабораторна має критичну кількість запозичень,
або захист був неуспішним,
або не виконано п. 0, 
то лабораторна отримує 0 балів і на цьому перевірка закінчується.

Інакше сумуємо бали:
- правильно (за винятком вимоги до кількості рисунків) виконаний пункт 1 дає виконавцю 1 бал, якщо побудовано 4 окремих рисунки, або 2 бали, якщо графіки були укладені на один рисунок;
- кожен правильно виконаний пункт з переліку 2-9 дає виконавцю 1 бал;
- акуратні, доречні та наявні підписи (не тільки заголовки) до всіх 5 рисунків дають виконавцю 3 бали; якщо рисунків менше або не всі гарно оформлені, то розраховується пропорційно наявному;
- зрозуміле виведення табличних даних з доречними підписами (можливо, деякі підписи розташовано в markdown-клітинах блокноту) дає виконавцю 1 бал;
- використання категоріальних даних для пункту 7 дає виконавцю 1 бал;
- усі тимчасові коментарі та все зайве, що використовувалось у процесі роботи та непотрібне у фінальній версії, має бути прибране; порушення вимог цього пункту оцінюватиметься штрафом в 1 бал (інакше кажучи, сміття треба прибрати);
- підготовка або обробка табличних даних, що здійснюється не засобами pandas, оцінюватиметься штрафом у 2 бали.
- порушення нефункціональної вимоги 2 оцінюватиметься штрафом у 2 бали.
  Максимум складає 15 балів.

Перескладання програмних проєктів, за які вже були виставлені остаточні бали, з метою збільшення кількості балів не передбачаються.
