# lecture_object

# What is Object in javaScript?

> An object in JavaScript is a data type that is composed of a collection of names or keys and values, represented in name:value pairs. The name:value pairs can consist of properties that may contain any data type — including strings, numbers, and Booleans — as well as methods, which are functions contained within an object.
>
>Объект в JavaScript — это тип данных, состоящий из набора имен или ключей и значений, представленных парами имя:значение. Пары имя:значение могут состоять из свойств, которые могут содержать данные любого типа, включая строки, числа и логические значения, а также методы, которые являются функциями, содержащимися внутри объекта.
>


## Methods Object

> 1) Object.entries()
>
> 2) Object.keys()
>
> 3) Object.values()
>
 #### Object.entries()
 > The Object.entries() static method returns an array of a given object's own enumerable string-keyed property key-value pairs.
 >
 >Статический метод Object.entries() возвращает массив собственных перечислимых пар ключ-значение свойства со строковым ключом данного объекта.
 >

![](/images/entries.jpg)

 #### Object.keys() 
 >The Object.keys() static method returns an array of a given object's own enumerable string-keyed property names.
 >
 >Статический метод Object.keys() возвращает массив собственных перечислимых имен свойств данного объекта со строковыми ключами.
 >

 ![](/images/keys.jpg)

 #### Object.values()
 >The Object.values() static method returns an array of a given object's own enumerable string-keyed property values.
 >
 >Статический метод Object.values() возвращает массив собственных перечислимых значений свойств данного объекта со строковыми ключами.
 >

 ![](/images/values.jpg)

 ## what is destructuring and spread in JavaScript?

 >JavaScript has two awesome data structures that help you write clean and efficient code. But handling them can get messy sometimes.
 >
 >В JavaScript есть две замечательные структуры данных, которые помогают писать чистый и эффективный код. Но иногда обращение с ними может стать грязным.
 >

 ![]()

 ![]()


 ## What is keyword "this" in JavaScript?

 >A function's this keyword behaves a little differently in JavaScript compared to other languages. It also has some differences between strict mode and non-strict mode.
 >In most cases, the value of this is determined by how a function is called (runtime binding). It can't be set by assignment during execution, and it may be different each time the function is called. The bind() method can set the value of a function's this regardless of how it's called, and arrow functions don't provide their own this binding (it retains the this value of the enclosing lexical context)
 >
 >Ключевое слово this функции ведет себя в JavaScript немного иначе, чем в других языках. Он также имеет некоторые различия между строгим режимом и нестрогим режимом.

 >В большинстве случаев значение this определяется тем, как вызывается функция (привязка во время выполнения). Его нельзя установить путем присваивания во время выполнения, и он может быть другим при каждом вызове функции. Метод bind() может установить значение функции this независимо от того, как она вызывается, а стрелочные функции не предоставляют свою собственную привязку this (он сохраняет значение this окружающего лексического контекста).
 >
 >this is NOT a variable. It is a keyword. You cannot change the value of this.
 >

 ![]()

 ## What is new Date() in Javascript?

> JavaScript Date objects represent a single moment in time in a platform-independent format. Date objects encapsulate an integral number that represents milliseconds since the midnight at the beginning of January 1, 1970, UTC (the epoch).
> 
>Объекты JavaScript Date представляют один момент времени в независимом от платформы формате. Объекты Date инкапсулируют целое число, которое представляет миллисекунды с полуночи начала 1 января 1970 года по UTC (эпоха).
>

> 1) new Date(): creates a new date.

![](/images/new%20date.jpg)

> 2) new Date(milliseconds):

![](/images/milli.jpg)

> 3) new Date(date string).

![](/images/date.jpg)

> 4) new Date(year, month, day, hours, minutes, seconds, milliseconds)

![](/images/yearmont.jpg)


### New Date() methods


![](/images/methods.jpg)

> 1) Date.now()

> The Date.now() static method returns the number of milliseconds elapsed since the epoch, which is defined as the midnight at the beginning of January 1, 1970, UTC.
>
> Статический метод Date.now() возвращает количество миллисекунд, прошедших с эпохи, которая определяется как полночь начала 1 января 1970 года по всемирному координированному времени.
>

![](/images/date-now.jpg)

> 2) Date.getFullYear()

> The getFullYear() method returns the year of the specified date according to local time.
>
> Метод getFullYear() возвращает год указанной даты по местному времени.
>

![](/images/getFullYear.jpg)

> 3) Date.get.Month()

>The getMonth() method returns the month in the specified date according to local time, as a zero-based value (where zero indicates the first month of the year).
>
>Метод getMonth() возвращает месяц указанной даты по местному времени в виде значения, отсчитываемого от нуля (где ноль указывает на первый месяц года).
>

![](/images/getmonth.jpg)

> 4) Date.get.Day()

>The getDay() method returns the day of the week for the specified date according to local time, where 0 represents Sunday. For the day of the month, see Date.prototype.getDate().
>
>Метод getDay() возвращает день недели для указанной даты по местному времени, где 0 означает воскресенье. Чтобы узнать день месяца, см. Date.prototype.getDate().
>
![](/images/day.jpg)


> 5) get.Date()

>The getDate() method returns the day of the month for the specified date according to local time.
>
>Метод getDate() возвращает день месяца для указанной даты по местному времени.
>

![](/images/GETdate.jpg)

> 6) get.Hours()

> The getHours() method returns the hour for the specified date, according to local time.
>
>Метод getHours() возвращает час для указанной даты по местному времени.
>

![](/images/hours.jpg)

> 7) get.Minutes()

>The getMinutes() method returns the minutes in the specified date according to local time.
>
>Метод getMinutes() возвращает минуты указанной даты по местному времени.
>

![](/images/minutes.jpg)


 > 1) setDate()

 > The setDate() method changes the day of the month of a given Date instance, based on local time.
 >
 > Метод setDate() изменяет день месяца данного экземпляра Date в зависимости от местного времени.
 >
 ![](/images/setDate.jpg)

 > 2) setMonth()

 > The setMonth() method sets the month for a specified date according to the currently set year.
 >
 > Метод setMonth() устанавливает месяц для указанной даты в соответствии с текущим установленным годом.
 >

 ![](/images/setMon.jpg)


 > 3) setFullYear

 >The setFullYear() method sets the full year for a specified date according to local time. Returns new timestamp.
 >
 >Метод setFullYear() устанавливает полный год для указанной даты по местному времени. Возвращает новую отметку времени.
 >

 ![](/images/setFull.jpg)
 


# object_pres
