# Excel
Excel Backup

Эта таблица была создана для ведения и подсчёта военнослужащих в больницах и поликлиниках, с конкретными званиями, диагнозами, родом войск и датой начала стационарного лечения. В ней нет макросов, все таблицы полностью работаю на встроенному функционале Excel.

Как работает данный Excel файл?

Для начала вам необходимо добавить новую строку. Добавление происходит ниже имеющихся записей. 

![image](https://user-images.githubusercontent.com/115461016/194864490-5e02d965-0dd3-49e9-b4e4-2dd0f205b985.png)
![image](https://user-images.githubusercontent.com/115461016/194861500-4ce787dc-4b98-4985-85ac-7007b6fdd739.png)

Далее выделяем первую строку над новой, и с помощью автозаполнения формул, заполняем формулы вниз до новой строки 

![image](https://user-images.githubusercontent.com/115461016/194864623-009dc489-2112-46b8-843d-6c86fd9bc262.png)

И заполняем все необходимые данные о новом военнослужащем. После чего, все необходимые подсчёты производятся автоматически.

![image](https://user-images.githubusercontent.com/115461016/194865107-5f3d271d-b2aa-4234-949d-dbba1b546060.png)

А так же есть дополнительная информация в конце таблицы

![image](https://user-images.githubusercontent.com/115461016/194865283-3d67a0a0-cca1-4e32-81ba-e3fa67e23ede.png)

Количество офицеров заполняется автоматически, как только появяется новый пациент офицерского состава.
И вся информация из этой таблицы оправлялась в другую, через ссылки. Вторая таблица полностью автономная.

Данная версия таблицы не является моим финальным вариантом. К сожалению backup данной таблицы достался мне в сыром виде. Мои дальнейшие оптимизации не сохранились.
Последующие оптимизированные мною действия в данной таблице, являются:
1. Оптимизация новых поступивших во всех учереждениях.
2. Полная автоматизация написания текста в конце строки для офицерского состава.

Конечно она не идеальна. Возникает резонный вопрос, что делать, если нет ни одного военнослужащего в какой-либо больнице или поликлинике. Приходилось вручную скрывать данные строки, т.к. удаление приведёт к потере связей. Или как добавить новые больницы? ... Я просто промолу об этом. Необходимости, в полной автоматизации, не было.

Но даже этого результата хватило, чтобы оптимизировать работу людей, которые занимались этой таблицей, с 3 часов до 15 минут и с 20 испорченных листов до 5 чистовых.

## Другие работы

К сожалению, из всех сохранившихся таблиц, которые я оптимизировал осталась только эта и она же считается самой первой из таблиц. 

В дальнейшем, я создал кассовую таблицу по ведению расходов на товар, оформил её в удобном стиле и добавил выпадающие MessageBox, с помощью макросов создал связь с листом, в котором хранятся данные о расходах. 

Это основные таблицы, которые я делал для различных целей.
