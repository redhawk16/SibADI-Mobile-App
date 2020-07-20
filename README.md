# Мобильное приложение "СибАДИ.Студент"

**Дипломная работа на тему: "Разработка мобильного приложения для студента на основе данных открытых источников вуза"**

Приложение обеспечивает возможность выполнения перечисленных ниже функций:
- возможность авторизации пользователя;
- возможность получения информации о расписании дисциплин группы;
- возможность выбора четной/нечетной недели в расписании дисциплин группы;
- возможность изменения/выбора подгруппы у дисциплины;
- возможность получения информации из электронной зачетной книжки студента;
- возможность получения информации об учебном графике группы;
- возможность отображения задолженностей, среднего балла студента;
- возможность отображения экзаменов и зачетов группы;
- возможность поиска расписания преподавателей/аудиторий;
- возможность добавления/редактирования/удаления заметок;
- возможность выбора периодичности обновления данных;
- возможность функционирования приложения без постоянного интернет-подключения;
- возможность изменения стартовой вкладки;
- возможность переключения темного режима пользовательского интерфейса.

> **Карта процессов приложения**
![Process Map](screens/Process-map.png?raw=true "Карта процессов мобильного приложения")

<br>**Первоначальная настройка приложения**
<img src="screens/screenshot-2020-07-20_16.03.52.825.png" alt="Initial Setup" title="Первоначальная настройка приложения" height="700">
На странице первоначальной настройки приложения, пользователю необходимо выбрать факультет, группу и номер зачетной книжки из выпадающего списка. После выбора всех данных станет доступна кнопка «Продолжить», нажав на которую будет осуществлен переход на страницу «Главная». Страница с первоначальной настройкой приложения будет открываться только в том случае, если пользователь установил приложение и не завершил его настройку или стер данные приложения. В иных случаях будет открываться страница «Главная» или любая другая страница, выбранная пользователем в настройках приложения.

<br>**Главная страница приложения**
<img src="screens/screenshot-2020-07-20_16.06.16.721.png" alt="Home Fragment" title="Главная страница" height="700">
На странице «Главная», представлена персональная информация пользователя приложения (студента):
– номер зачетной книжки;
– наименование группы и факультета;
– задолженности по дисциплинам;
– средний балл электронной зачетной книжки;
– информация о ближайших зачетах и экзаменах.

<br>**Расписание дисциплин группы**
<img src="screens/screenshot-2020-07-20_16.06.34.788.png" alt="Schedule Fragment" title="Расписание дисциплин" height="700">
<img src="screens/screenshot-2020-07-20_16.06.39.607.png" alt="Bottom Sheet Discipline" title="Карточка дисциплины" height="700">
На странице «Расписание», отображается расписание дисциплин на текущий день и тип недели. При необходимости, пользователь может посмотреть расписание звонков, нажав на значок часов в правом верхнем углу. Также, у пользователя имеется возможность изменить тип отображаемой недели, переключая на «четную» или «нечетную» неделю соответственно, помимо этого, перелистывая область с расписанием можно просматривать расписание на любой другой день.
В целях повышения комфортности использования приложения, в пользовательском интерфейсе предусмотрена нумерация пар по счету, а также используются разные цвета, для быстрого ориентирования в типах дисциплин, которые приведены ниже:
– Практика – серый.
– Лекция – зеленый.
– Лабораторная – синий.
– Экзамен – красный.
– Зачет – оранжевый.
Для отображения дополнительных возможностей, необходимо нажать и удерживать по дисциплине, пока не всплывет карточка выбранной дисциплины. В данной карточке будет отображены: наименование, время начала и окончания пары, а также возможность изменения подгруппы и поиска расписания преподавателя или аудитории.

<br>**Электронная зачетная книжка студента**
<img src="screens/screenshot-2020-07-20_16.06.58.188.png?raw=true" alt="Record Book" title="Электронная зачетная книжка студента" height="700">
На странице «Зачетка», отображается электронная зачетная книжка студента, которая сгруппирована по типам контроля. Каждая дисциплина содержит информацию о номере семестра, в котором она была проведена, ФИО преподавателя, количестве часов по учебному плану и полученной оценке. О том, какая оценка получена по тому, или иному предмету, информирует цвет текста оценки. Цвет варьируется в зависимости от полученного результата:
– Отлично, зачет – зеленая.
– Хорошо – синяя.
– Удовлетворительно – желтая.
– Неудовлетворительно, незачет – красная.

<br>**Страница "Еще"**
<img src="screens/More.png?raw=true" alt="More Fragment" title="Страница &quot;Еще&quot;" height="700">
На странице «Еще», отображены дополнительные пункты приложения, на которых пользователь имеет возможность:
– изменить основную цветовую схему приложения переключив пункт «темный режим»;
– найти преподавателя по фамилии и просмотреть его расписание;
– найти и просмотреть расписание аудитории по номеру;
– просмотреть учебный график;
– просмотреть собственные заметки;
– перейти к настройкам приложения;
– увидеть информацию о приложении.

<br>**Поиск расписания дисциплин по номеру аудитории/ФИО преподавателя**
<img src="screens/screenshot-2020-07-20_16.07.57.134.png?raw=true" alt="Search Fragment" title="Поиск расписания дисциплин" height="700">

<br>**Расписание дисциплин аудитории/преподавателя**
<img src="screens/screenshot-2020-07-20_16.08.01.457.png?raw=true" alt="Schedule Fragment" title="Расписание дисциплин аудитории/преподавателя" height="700">
На страницах «Расписание преподавателя» и «Расписание аудиторий», отображается расписание дисциплин у конкретного преподавателя или у конкретной аудитории, для которой был осуществлен поиск. Также, как и на странице «Расписание», имеется возможность изменить тип отображаемой недели, переключая на «четную» или «нечетную» неделю соответственно, помимо этого можно просматривать расписание на любой другой день перелистывая область с расписанием. Возможность изменения или выбора подгруппы отсутствует, в связи с тем, что данное расписание дисциплин доступно только при наличии интернет-подключения в режиме просмотра.

<br>**Учебный график группы**
<img src="screens/screenshot-2020-07-20_16.08.21.601.png?raw=true" alt="Exams Chart" title="Учебный график группы" height="700">
На странице «Учебный график», отображается график зачетов и экзаменов, который сгруппирован по типам контроля. Каждая дисциплина содержит информацию о дате проведения контроля, ФИО преподавателя, количестве часов по учебному плану и об аббревиатуре кафедры, на которой данная дисциплина читается.

<br>**Страница "Заметки"**
<img src="screens/screenshot-2020-07-20_16.09.05.47.png?raw=true" alt="Notes Fragment" title="Страница &quot;Заметки&quot;" height="700">
На странице «Заметки», отображаются все созданные заметки пользователем. Для доступа к дополнительным возможностям, необходимо нажать и удерживать одну из заметок, пока не всплывет карточка выбранной заметки. В карточке заметки можно: открыть данную заметку для просмотра и редактирования или удалить ее навсегда.
Для добавления новой заметки пользователю необходимо нажать по значку, находящемуся в правом нижнем углу, после чего будет осуществлен переход на страницу с добавлением новой заметки. На данной странице пользователю будет необходимо заполнить заголовок и описание заметки, и затем нажать на значок в правом нижнем углу, после чего новая заметка будет добавлена и отобразится на странице «Заметки».

<br>**Добавление/редактирование новой заметки**
<img src="screens/screenshot-2020-07-20_16.08.58.355.png?raw=true" alt="Add/Edit Note" title="Добавление/редактирование новой заметки" height="700">

<br>**Настройки приложения**
<img src="screens/screenshot-2020-07-20_16.09.09.863.png?raw=true" alt="Settings Fragment" title="Настройки приложения" height="700">
<img src="screens/screenshot-2020-07-20_16.09.22.034.png?raw=true" alt="Bottom Sheet Settings" title="Изменение стартовой вкладки приложения" height="700">
На странице «Настройки», пользователь может: изменить подгруппу по умолчанию для удобного просмотра расписания дисциплин, стартовую вкладку, периодичность обновления информации, касающуюся электронной зачетной книжки и расписания дисциплин, а также удалить все личные данные.

<br>**Темный режим**
<img src="screens/screenshot-2020-07-20_16.09.35.86.png?raw=true" alt="Dark Home Fragment" title="Темная главная страница приложения" height="700">
<img src="screens/screenshot-2020-07-20_16.09.33.076.png?raw=true" alt="Dark Schedule Fragment" title="Темная страница расписания дисциплин группы" height="700">
<img src="screens/screenshot-2020-07-20_16.09.28.647.png?raw=true" alt="Dark More Fragment" title="Темная страница &quot;Еще&quot;" height="700">

<br>**Видео демонстрация мобильного приложения "СибАДИ.Студент"**
<a href="https://youtu.be/RrcuJFIZo18">
  <img src="screens/screenshot-2020-07-21_01.33.13.875.png" alt="Watch the video" height="700">
</a>
