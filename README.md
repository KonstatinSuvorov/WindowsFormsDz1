# WindowsFormsDz1

Задание 1
Вывести на экран свое (краткое!!!) резюме с помощью последовательности MessageBox’ов (числом не менее трех). Причем на заголовке 
последнего должно отобразиться среднее число символов на странице 
(общее количество символов в резюме / количество MessageBox’ов). 


Задание 2
Написать функцию, которая «угадывает» задуманное пользователем число от 1 до 2000. Для запроса к пользователю использовать 
MessageBox. После того, как число отгадано, необходимо вывести 
количество запросов, потребовавшихся для этого, и предоставить 
пользователю возможность сыграть еще раз, не выходя из программы 
(MessageBox’ы оформляются кнопками и значками соответственно 
ситуации).


Задание 3
Представьте, что у вас на форме есть прямоугольник, границы которого на 10 пикселей отстоят от границ рабочей области формы. Необходимо создать следующие обработчики: 
■ Обработчик нажатия левой кнопки мыши, который выводит сообщение о том, где находится текущая точка: внутри прямоугольника, снаружи, на границе прямоугольника. 
Домашнее задание №1 Домашнее задание №<Номер дз>
Если при нажатии левой кнопки мыши была нажата кнопка
Control (Ctrl), то приложение должно закрываться;
■ Обработчик нажатия правой кнопки мыши, который выводит в заголовок окна информацию о размере клиентской 
(рабочей) области окна в виде: Ширина = x, Высота = y, где 
x и y – соответствующие параметры вышего окна;
■ Обработчик перемещения указателя мыши в пределах рабочей области, который должен выводить в заголовок окна 
текущие координаты мыши x и y. 


Задание 4
Разработать приложение, созданное на основе форме. 
■ Пользователь «щелкает» левой кнопкой мыши по форме и, 
не отпуская кнопку, ведет по ней мышку, а в момент отпускания кнопки по полученным координатам прямоугольника (вам, конечно, известно, что двух точек на плоскости 
достаточно для создания прямоугольника) необходимо создать «статик», который содержит свой порядковый номер 
(имеется в виду порядок появления на форме). 
■ Минимальный размер «статика» составляет 10х10, при попытке создания элемента меньших размеров пользователь 
должен увидеть соответствующее предупреждение. 
■ При щелчке правой кнопкой мыши над поверхностью 
«статика» в заголовке окна должна появиться информация о его площади и координатах (относительно формы). 
В случае, если в точке щелчка находится несколько «статиков», то предпочтение отдается «статику» с наибольшим 
порядковым номером. 
Домашнее задание №1 Домашнее задание №<Номер дз>
■ При двойном щелчке левой кнопки мыши над поверхностью «статика» он должен исчезнуть с формы. В случае, 
если в точке щелчка находится несколько «статиков», то 
предпочтение отдается «статику» с наименьшим порядковым номером. 


Задание 5 
Разработать приложение «убегающий статик»:) Суть приложения: 
на форме расположен статический элемент управления («статик»). 
Пользователь пытается подвести курсор мыши к «статику», и, если 
курсор находиться близко со статиком, элемент управления «убегает». Предусмотреть перемещение «статика» только в пределах формы. 


Задание 6 
Написать программу, которая по введенной дате определяет день 
недели. Результат выводить в текстовое поле (желательно по-русски). 


Задание 7 
Написать программу, вычисляющую сколько осталось времени 
до указанной даты (дата вводится с клавиатуры в Edit). Предусмотреть возможность выдачи результата в годах, месяцах, днях, минутах, 
секундах (для первых двух вариантов ответ дробный). Для переключения между вариантами желательно использовать переключатели 
(RadioButton).


Задание 8
Постановка задачи:
Владелец автозаправки «BestOil» заказал следующую программу. 
Когда автозаправка только начинает свою деятельность, владелец 
обычно хочет получать максимально большой доход, который планирует увеличить за счет дополнительных услуг. Поэтому на автозаправке будет действовать небольшое кафе. Но, в то же время он может нанять только одного работника на должность кассира, а потому 
Домашнее задание №1 Домашнее задание №<Номер дз>
назначение программы – учет продаж бензина и ассортимента товаров в миникафе.
Требования к поставленной задаче:
Для удобства окно разделено на три части: первая для осуществления вычислений, касающихся непосредственно заправки автомобилей топливом; вторая – покупки в мини-кафе; третья часть для вычисления суммы оплаты.
Итак, первая группа элементов Автозаправка.
ComboBox – выпадающий список с перечнем имеющегося горючего. По умолчанию, сразу при запуске программы должен быть выбран 
определенный вид горючего и в TextBox (или например Label) должна 
отображаться цена на данный вид продукта. При каждой смене выбора бензина, цена в данном поле будет соответственно меняться.
Далее, дается возможность выбора: купить горючее, указав необходимое количество литров или указав, на какую сумму клиент будет 
заправляться. При этом, после выбора одного из двух вариантов предоставления услуги, ненужное поле становится заблокированным. В 
случае ввода суммы денег, группа «К оплате» изменит название на «К 
выдаче»; вместо суммы следует выводить количество литров, соответственно изменяются единицы измерения с «грн..» на «л»..
Вторая группа Мини-кафе.
Для удобства, все возможные товары выведены сразу в данной 
части. Для каждого продукта предусмотрены CheckBox с названием 
товара, рядом выводится цена (неактивный TextBox). При получении 
заказа для возможности ввода количества заказанных единиц товара, 
следует поставить «галочку» в CheckBox напротив соответствующего 
товара.
Последняя – «К оплате».
Содержит кнопку, которая отвечает за осуществление вычисления и вывода сумм в соответствующих полях. После того, как выведена сумма, через (например) 10 секунд должен появиться запрос на 
Домашнее задание №1 Домашнее задание №<Номер дз>
очистку формы, то есть при появлении следующего клиент: да – все 
поля принимают значения по умолчанию, нет – неизменное состояние остается еще на 10 секунд. При выходе из программы (закончился 
рабочий день) должно появиться окно с сообщением, какова общая 
сумма выручки за данный день. Или эту сумму можно сразу выводить в самой форме и изменять после каждого осуществления расчета 
с клиентом.
Кроме этого, придайте форме эстетический вид (цвета, шрифты, рисунки ...). При обоснованной необходимости и интересном 
решении функциональности программы разрешается вносить изменения во внешний вид формы или набор элементов
