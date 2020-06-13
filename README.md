# AnswersOnTViMS
## **Лекция 1**

### *предмет теории вероятностей*
является изучение вероятностных закономерностей массовых однородных случайных событий.

### понятие опыта,случайного явления,случайного события 

*Случайное явление* – это явление, которое при неоднократности
воспроизведения одного и того же опыта протекает каждый раз по-иному,
непредсказуемым образом.

*Опыт* – воспроизводимая совокупность условий, в которых фиксируется
тот или иной результат.

*Случайное событие* – всякий факт, который в опыте со случайным
исходом может произойти или не произойти. Обозначение: А, В, С, …. 

### вероятность,  частота события

*Вероятность случайного события* – количественная мера (степени) объективной
возможности его осуществления. 

p (A) = m / n – *частота события* А в n опытах; (отношение ...)
m – число опытов в которых произошло событие А;
n – число проведенных опытов. 

### классическое определение вероятности 

Вероятностью наступления события  в некотором испытании называют отношение p (A) = m / n, где:

m – общее число всех равновозможных, элементарных исходов этого испытания, которые образуют полную группу событий;

n – количество элементарных исходов, благоприятствующих событию 

### *классификация схем выбора при непосредственном подсчете вероятности*.  

Существуют две схемы выбора: *схема выбора без возвращения эле-
ментов* и *схема выбора с возвращением элементов*. В первом случае из-
влеченные m элементов (без разницы, по одному или вместе) не возвра-
щаются в исходную совокупность.

*С упорядочиванием*: 

![Alt text](/1.2.png?raw=true "1.2")

*Без упорядочиванием*: 

![Alt text](/1.3.png?raw=true "1.3")

Во втором случае на каждом шаге
элементы извлекаются по одному, фиксируется выбранный элемент, затем
он возвращается, и вся исходная совокупность тщательно перемешивает-
ся. Таким образом, во втором случае один и тот же элемент может извле-
каться неоднократно. После осуществления выбора элементы могут быть упорядочены или
нет.

*Без упорядочивания*:

![Alt text](/1.3.2.png?raw=true "1.2")

*С упорядовачиванием*:

***n^m***

## **Лекция 2**

### *элементарное событие*

При опыте со случайным исходом имеется множество ω ∈ Ω всех воз-
можных исходов опыта. Каждый элемент этого множества называют элементарным событием,

### *пространством элементарных событий*

само множество Ω – пространством эле
ментарных событий.

### *достоверное событие*

Подмножеством множества Ω можно рассматривать и само Ω – оно будет в
этом случае достоверным событием.

### *невозможное событие*

1.) Ко всему пространству Ω элементарных событий добавляется еще и пустое множество; это множество рассматривается тоже
как событие, но невозможное.

2.) Событие называется невозможным, если оно не может произойти в условиях данного опыта. (определение из гугла)

### *полная группа событий*

![Alt text](/image.png?raw=true "image")

### *несовместные события*

Два события А и В называются несовместными, если соответствующие
им множества не пересекаются, т. е. AB = Ø

### *противоположное событие*

 Противоположным по отношению к событию А называется событие неA ,
состоящее в непоявлении А и соответственно дополняющее событие А до Ω
(см. рис)

![Alt text](/ANeA.png?raw=true "ANeA")

### сформулировать *аксиомы теории вероятностей*

1. Вероятность любого события заключена между нулем и единицей:
0 <= P(A) <= 1 .

2. Если А и В – несовместные события, т. е. AB = Ø, то

P(A + B) = P(A) + P(B).

3. Вероятность суммы несовместных событий равна сумме их вероятностей

![Alt text](/3Aks1.png?raw=true "3Aks1")

### сформулировать *следствия  аксиом теории вероятностей*

1.
![Alt text](/1sled.png?raw=true "1sled")

2.
Сумма вероятностей противоположных событий равна единице: P(A)+P(!A)=1
т.к. A+!A=Ω

3.
![Alt text](/3sled.png?raw=true "3sled")

### сформулировать *правило сложения вероятностей*.  

![Alt text](/slosh.png?raw=true "slosh")

Формула для общего случая (от Вити): 

![Alt text](/vkliskl.png?raw=true "vkliskl")

## **Лекция 3**

### понятие условной вероятности 
Условной вероятностью события В при наличии А называется вели-
чина P(B/A) = P(AB)/P(A) В предположении что P(A)!=0

Значит можно трактовать условную ве-
роятность P(B/ A) как вероятность события В, вычисленную при условии, что событие А произошло.

### понятие независимости событий;

Событие А называется независимым от события В, если вероятность P(A)не зависит от того, произошло В или нет, т. е.

P(A/B) = P(A)

если A = A(B) то и B = B(A) ***ВСЕГДА***

два события называются *независимыми*, если появление одного из них не меняет вероятности появления другого.
Правило умножения вероятностей для независимых событий :

P(AB) = P(A)*P(B)

***вероятность произведения нескольких независимых событий равна произведению вероятностей этих событий.***

### правило умножения вероятностей; 

![Alt text](/2.7.png?raw=true "2.7")

т. е. ***вероятность произведения нескольких событий равна произведению
вероятностей этих событий, причем вероятность каждого последующего
события вычисляется при условии, что все предыдущие произошли.***

### *формула полной вероятности*

Проведение опыта возможно только в условиях *исключающих друг
друга гипотез*

![Alt text](/2.10.png?raw=true "2.10")

Гипотезы составляют *полную группу несовместных событий* с из-
вестными вероятностями появления

![Alt text](/2.11.png?raw=true "2.11")

### теорема гипотез  (формула Байеса)

Позволяет определить вероятность срабатывания события по определенной гипотезе, когда событие уже произошло.
Формула БАйеса (снизу - полная вероятность события (А), а сверху - вероятность события по определенной гипотезе )

![Alt text](/2.12.png?raw=true "2.12")

### априорные вероятности

![Alt text](/ap.png?raw=true "ap")

### апостериорные вероятности

![Alt text](/apos.png?raw=true "apos")

## **Лекция 4**

### независимое  испытание

Несколько опытов считаются независимыми, если вероятность того
или иного исхода каждого из опытов не зависит от того, какие результаты
имели другие опыты, например несколько последовательных бросаний
монеты, несколько выниманий карты из колоды при условии ее возврата в
колоду и перемешивания.

### формула Бернулли; 

Таким образом, можно сформулировать частную теорему о повторе-
нии опытов. Если производится *n* независимых опытов, в каждом из ко-
торых событие А может появиться с вероятностью *p* , то вероят-
ность того, что событие А появится ровно *m* раз, равна

![Alt text](/3.1.png?raw=true "3.1")

также это называют *биномиальным распределением*

### границы применимости асимптотических теоремы 

### Локальная теорема Муавра  – Лапласа. Типичные задачи, к ней приводящие.

Сама теорема с вводимым x:

![Alt text](/x.png?raw=true "x")
![Alt text](/muavra.png?raw=true "muavra")

Типичная задача, приводящая к теореме (пункт а):

![Alt text](/primer.png?raw=true "primer")

### Интегральная теорема Муавра – Лапласа. Типичные задачи, к ней приводящие.  

Сама теорема:

![Alt text](/muavr.png?raw=true "muavr")
![Alt text](/muavra2.png?raw=true "muavra2")

Типичная задача, приводящая к теореме (+ пункт Б из примера выше):

![Alt text](/zadacha.png?raw=true "zadacha")

### Теорема Пуассона 

Однако значительное количество задач связано с необходимостью вычислять вероятности *Pm,n* именно при малых *p*. То есть, чтобы теорема Муавра – Лапласа дала приемлемый результат, необходимо произвести очень большое число *n*
Задача нахождения асимптотической формулы вычисления вероятностей *Pm,n* при малых *p* решена теоремой Пуассона.

![Alt text](/3.9.png?raw=true "3.9")


## **Лекция 5**

### понятие случайной величины 

Под случайной величиной понимается величина, которая в результа-
те опыта со случайным исходом принимает то или иное значение. Воз-
можные значения случайной величины образуют множество , которое
называют множеством возможных значений случайной величины.

### понятие закона распределения 

Законом распределения случайной величины называется любое пра-
вило (таблица, функция), позволяющее находить вероятности всевозмож-
ных событий, связанных со случайной величиной.

### непрерывная случайная величина

![Alt text](/4.11.png?raw=true "4.11")

### дискретная случайная величина

Случайная величина называется дискретной, если ее множество значений счетно и конечно

### ряд распределения для дискретной случайной величины 

- таблица, в верхней строке которой перечислены в порядке возрастания все возможные значения случайной величины X: x1, x2, ..., xn,а в
нижней – вероятности этих значений: p1, p2,... ,pn.

pi = P{X=xi} - вероятнность того, что в результате опыта случайная величина X примет значение xi(i=1,2,...,n,...)

т.к. события x1, x2,... ***несовместны и образуют полную группу***, то сумма вероятнностей p1,p2...pn = 1

### понятие функции распределения
Функцией распределения случайной величины *Х* называется вероятность того, что она примет значение меньшее, чем заданное *х*(аргумент функции) 
*F(x)=P{X<x}*
### свойства функции распределения
1. F(x) - неубывающая функция своего аргумента. 
(если x2>x1 то F(x2)>=F(x1))

2. F(-inf) = 0 F(inf) = 1

не свойство но важно
(a - alpha B - betta)
С помощью функции распределения можно вычислить вероятность
попадания случайной точки на участок от a до B. Для определенности
левый конец участка будем включать в него, а правый – нет.
F(B) = F(a)+P(a<=X<B)

### понятие  плотности распределения вероятностей

Плотностью распределения f(x) непрерывной случайной величины Х в точке х называется производная ее функции распределения в этой точке

f(x) = F'(x)=dF(x)/dx

Плотность распределения f(x), как и функция распределения F(x), является одной из форм закона распределения, но она существует только для непрерывных случайных величин.

![Alt text](/4.9.png?raw=true "4.9")

В геометрической интерпретации эта вероятность равна площади фигуры, ограниченной сверху кривой распределения и опирающейся на участок[a,B]

![Alt text](/4.9.png?raw=true "4.10")

### свойства плотности распределения вероятностей

1.f(x)>=0

2.![Alt text](/4.11REAL.png?raw=true "4.11REAL")

## **Лекция 6**
### числовые характеристики положения 
### моменты непрерывных случайных величин
### моменты  дискретных случайных величин.
### свойства математического ожидания
### свойства дисперсии

## **Лекция 7**

### производящая функция*
### параметры биномиального распределения, 
### пуассоновского распределения, 
### геометрического распределения
### гипергеометрического распределений, 
### поток событий 
### условия, необходимые для существования пуассоновского потока.  Стационарность
### Ординарность
### Отсутствие последействия

## **Лекция 8**
### функции плотности и числовые характеристики равномерно распределенной случайной величины,  
### функции плотности и числовые характеристики  случайной величины, имеющей показательное распределение,  
### функции плотности и числовые характеристики  нормальнораспределенной  случайной величины 
### функции плотности и числовые характеристики случайной величины, имеющей гамма-распределение.  
## **Лекция 9**
система  случайных  величин 
### законраспределения систем двух случайных величин; 
### условия зависимости и независимости случайных величин, 
### условныйзакон распределения 
### правило умножения плотностей.  Теорема  умножения  плотностей

## **Лекция 10**

### числовые  характеристики  системы  двухслучайных величин
### начальные и центральные моменты, 
### ковариация, 
### коэффициент корреляции
### регрессия
### двумерное нормальное распределение;  
### закон  распределения n -мерного случайного вектора; 
### числовые  характеристикиn -мерного случайного вектора;
### плотность распределения многомерного гауссова распределения.  
## **Лекция 11**
### понятие функции случайной величины
### закон распределения функции одного случайного аргумента 
### закон распределения суммы двух случайных величин*
### понятие композиции законов распределения.*  
## **Лекция 12**
### метод линеаризации функций случайных величин; 
### понятие комплексной случайной величины
### числовые характеристики комплексной случайной величины
### характеристическая функция комплексной случайной величины
### свойства характеристической функции.  
## **Лекция 13**
### неравенство  Чебышева;  
### закон  больших  чисел  
### следствия закона больших чисел
### теорема Чебышева
### обобщенная теорема Чебышева
### теорема Бернулли
### теорема Пуассона
### центральная предельная теорема 

## **Лекция 14**
### понятие генеральной и выборочной совокупности 
### типичные задачи математической статистики; 
### понятие выборочной функции распределения, 
### понятие вариационного ряда и гистограммы; 
### наиболее важные для математической статистики распределения.   

## **Лекция 15**
### понятие  оценки  неизвестного  параметра  распределения 
### классификация  оценок;
### качество оценок
### точечные оценки математического ожидания и дисперсии.

## **Лекция 16**
### понятие доверительной вероятности и доверительного  интервала,  
### интервальные  оценки  математического ожидания и дисперсии.   
## **Лекция 17**
### понятие статистических гипотез и правилаих проверки; 
### проверка гипотезы о равенстве средних значений и 
### дисперсий  нормально  распределенной  случайной  величины,  
### критерий согласия  χ2 .  
Вопросы со звездочкой (*) для повышения балла.
