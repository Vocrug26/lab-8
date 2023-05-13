# lab-8
<h1 align="center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<p align="center">Лабораторная работа №6</p>
<p align="center">"JavaScript"</p>
<br>
<p align="right">Работу выполнил Гурков Владислав Викторович</p>
<p align="right">Работу проверил Соболев Евгений Игоревич</p>


### **Цели и задачи:**
1.	Напишите оператор if, такой, чтобы в качестве выражения в скобках у него были значения true, false (Например, if( true ) или if( false )). Посмотрите как работает этот оператор, поместив какую-нибудь команду после круглых скобок (Например, console.log(1)). 

2.	Создайте переменные m и n. В m поместите произвольное числовое значение. Напишите оператор ветвления if так, чтобы если m было больше 50, то в переменную n помещалось слово «большое», иначе — слово «маленькое».

3.	Определите сколько раз выполнится цикл while? Примечание: это можно сделать прочитав скрипт или запустив его консоли браузера.
var i = 2;
while( i < 9 ){
 	  console.log( i++ );
  }


4.	Напишите скрипт, который используя оператор while выведет все числа от 45 до 67.

5.	Напишите скрипт, который используя оператор while выведет все числа от 45 до 670, кратные 10.

6.	Напишите скрипт, который используя оператор for выполнит два предыдущих задания.

7.	Переменная n хранит целое число от 0 до 9. Используя оператор switch, написать скрипт, который в зависимости от числа будет выводить слово (Например, если n равно 3, то будет выводиться слово «три»)
var n = 5;
switch( n ){
 //Напишите тут свой код
}

8.	Используя document.write() и любую из циклических конструкций выведите  десять одинаковых изображений (надо выводить <img src="..." alt="..." />)

9.	В переменных size и unit хранятся размер и единицы измерения информации 120 и «Кб» соответственно. Зная что могут быть заданные Кб, Мб, Гб (кило-, мега- и гигабайты) и 1килобайт равен 1024 байта, найти количество байт в size.

10.	Постройте при помощи циклов JavaScript скрипт для календаря на HTML. Примечание: выполнить задание для одного месяца, используя HTML-элемент table

11.	Напишите функцию hello1(), которая при вызове будет возвращать строку «Привет, JavaScript!».

12.	Напишите функцию hello2(), которая при вызове будет принимать переменную name (например, «Василий») и выводить строку (в нашем случае «Привет, Василий»).  В случае отсутствующего аргумента выводить «Привет, гость»

13.	Напишите функцию mul(n,m), которая принимает два аргумента и возвращает произведение этих аргументов. Проверьте ее работу.


14.	Создайте функцию repeat(str, n), которая возвращает строку, состоящую и n повторений строки str. n — по умолчанию 2, str — пустая строка

15.	Создайте функцию rgb(), которая будет принимать три числовых аргумента и возвращать строку вида «rgb(23,100,134)». Если аргументы не заданы, считать их равными нулю. Не проверять переменные на тип данных

16.	Создайте функцию avg() , которая будет находить среднее значение по всем своим аргументам (аргументы величины числовые).

17.	Создайте функцию m(a,b) оболочку для mul(). m() должна принимать два аргумента а возвращать результат работы mul() с этими двумя аргументами После выполнения задания поэкспериментируйте, создайте функцию log(), которая будет принимать одно значение, а вызывать  console.log() с этим значением.

18.	Напишите функцию operation(m,n,o), в которой m и n — числовые переменные, а o — функциональный литерал, который берет два аргумента и выполняет математическую операцию над ними 


19.	Напишите функцию addN(n), которая вернёт другую функцию. Возвращенная функция должна складывать получаемый аргумент с аргументом n возвращающей функции. 

20.	Напишите функцию words(),  которая в зависимости от переданного в нее целочисленного аргумента n, будет выводить слово «товар» в нужно форме («12 товаров», но «22 товара»). По умолчанию аргумент d должен иметь значение 0

**Задания**
```function zz1(){ 
 let x=4;
console.log('Число четное?')
if (x % 2)
{
    console.log('false')
}

{
    console.log('true')
}
}

function zz2(){
	 let m=100;
let n;
if (m>50)
{n="большое"}
else{n="маленькое"}
console.log(n)
}

function zz3(){
	var i = 2;
var count=0;
while( i < 9 ){
console.log( i++ );
count++;
}
console.log("while выполнится: " + count+" раз");
}

function zz4(){
	 var i = 45;
while( i < 68 ){
console.log( i++ );
}
}

function zz5(){
	var i = 45;
while( i < 671 ){
if (i % 10)
{
    i++;
}
else
{
    console.log(i++);      
}
}

}

function zz6(){
	  for (let i = 45; i < 671 ;i++)
{
    while( i < 68 ){
    console.log( i++);
    } 
    if (i % 10)
    {i++;}
    else{
    console.log(i++);}

}
}

function zz7(){
	  var n = 2;
switch(n)
{
    case 0:var per='ноль';break;
    case 1:var per='один';break;
    case 2:var per='два';break;
    case 3:var per='три';break;
    case 4:var per='четыре';break;
    case 5:var per='пять';break;
    case 6:var per='шесть';break;
    case 7:var per='семь';break;
    case 8:var per='восемь';break;
    case 9:var per='девять';break;
}
console.log(per);
}

function zz8(){
	  var i = 0;
while(i <= 9)
{   
document.write('<img src="001.jpg"/>');
i++;
}
}

function zz9(){
	 var size=120;
var unit="Кб"
if (unit=="Кб")
{size = size * 1024;}
    else
{if (unit=="Мб")
{size = size * 1024*1024;}
    else
{if (unit=="Гб")
{size = size * 1024*1024*1024}}}
document.getElementById("z9").innerHTML = size + "байт";
}

function zz10(){
	
	
}

function zz11(){
	 document.getElementById("z11").innerHTML = "Привет, JavaScript!";
}

function zz12(){
	var name = "Пользователь"
    if (name=="")
    {document.getElementById("z12").innerHTML = "Привет, гость";}
    else
    {document.getElementById("z12").innerHTML = "Привет, "+ name;}
}

 function mul(n=9,m=8){
    document.getElementById("z13").innerHTML = n*m;
}
function repeat(str, n)
{
    n=2;
	str="qq";
    for (let i=1; i < n ; i++)
    {
str+=str;
    }
    document.getElementById("z14").innerHTML = str;
}
function rgb(r=2, g=123, b)
{   
    if (r==undefined)
    {r=0;}
    if (g==undefined)
    {g=0;}
    if (b==undefined)
    {b=0;}
    document.getElementById("z15").innerHTML = "rgb(" + r +", " + g + ", " + b + ")";
}
function avg()
{
    var a=32; v=54; g=22;
    document.getElementById("z16").innerHTML = (a+v+g)/3;
}
function m(a,b)
{
    console.log(mull(a,b));
}
function mull(a,b)
{
    return a*b;
}
function zz17()
{
    m(9,3);
}
function zz18()
{
    console.log(operation(3,6,'+'));
    console.log(operation(13,7,'-'));
    console.log(operation(2,4,'*'));
    console.log(operation(8,1,'/'));
    console.log(operation(9,5,'ошибочка'));
}
function operation(m,n,o)
{
    let res;
    switch(o){
case '+': res = m+n; break;
case '-': res = m-n; break;
case '*': res = m*n; break;
case '/': res = m/n; break;
default: return "Не получилось определить оператор!";
    }
    return res;
}
function addN(n)
{
    return addN2(10,n)
}
function addN2(a,b)
{
    return a+b;
}
function zz19()
{
    console.log(addN(3));
}
function zz20()
{
    console.log(words(0));
    console.log(words(1));
    console.log(words(4));
    console.log(words(7));
    console.log(words(13));
    console.log(words(1024));
}
function words(n)
{
    let val = Math.abs(n) % 100;
    let num = val % 10;
    if(val > 10 && val < 20) return n+" товаров";
    if(num > 1 && num < 5) return n+" товара";
    if(num == 1) return n+" товар";
    return n+" товаров";
}```
### **Вывод:**
После выполнения данной лабораторной работы я улучшил свои навыки работы с JavaScript.

