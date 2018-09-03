#### Форматиране на изходните данни

След като изчислихме какви са съответните цени и крайната сума за престоя - нека да си изведем във форматиран вид резултата, като преди това го запишем в изходните ни **параметри** - **`studioInfo`** и **`apartmentInfo`**.

![](/assets/chapter-4-2-images/05.Hotel-room-06.png)

За изчисленията на изходните параметри използваме **метода** **`decimal.Round(Decimal, Int32)`**.
Този метод **закръгля десетично** число до **зададен брой цифри** след десетичния знак. За целта, подаваме на метода данни от тип **`decimal`** (**`studioRent`**, **`apartamentPrice`**) и цяло число (**`int`**). В нашия случай ще закръглим десетичното число до **две цифри** след десетичната точка.

#### Отпечатване на резултата

Накрая остава да покажем изчислените резултати на конзолата.

### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/509#4](https://judge.softuni.bg/Contests/Practice/Index/509#4).