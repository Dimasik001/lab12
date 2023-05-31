<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №12</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">PHP (рекурсивный акроним словосочетания PHP: Hypertext Preprocessor) - это распространённый язык программирования общего назначения с открытым исходным кодом. PHP специально сконструирован для веб-разработок и его код может внедряться непосредственно в HTML.PHP отличается от JavaScript тем, что PHP-скрипты выполняются на сервере и генерируют HTML, который посылается клиенту. Если бы у вас на сервере был размещён скрипт, подобный вышеприведённому, клиент получил бы только результат его выполнения, но не смог бы выяснить, какой именно код его произвёл. Вы даже можете настроить свой сервер таким образом, чтобы обычные HTML-файлы обрабатывались процессором PHP, так что клиенты даже не смогут узнать, получают ли они обычный HTML-файл или результат выполнения скрипта.</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
1.	Создайте массив, заполненный числами от 1 до 100. Найдите сумму элементов данного массива.
2.	Дан массив с элементами 'a', 'b', 'c', 'd', 'e'. С помощью функции array_map сделайте из него массив 'A', 'B', 'C', 'D', 'E'.
3.	Дан массив $arr. Подсчитайте количество элементов этого массива.
4.	Дан массив $arr. С помощью функции count выведите последний элемент данного массива.
5.	Дан массив с числами. Проверьте, что в нем есть элемент со значением 3.
6.	Дан массив [1, 2, 3, 4, 5]. Найдите сумму элементов данного массива.
7.	Дан массив [1, 2, 3, 4, 5]. Найдите произведение (умножение) элементов данного массива.
8.	Дан массив $arr. С помощью функций array_sum и count найдите среднее арифметическое элементов (сумма элементов делить на их количество) данного массива.
9.	Создайте массив, заполненный числами от 1 до 100.
10.	Создайте массив, заполненный буквами от 'a' до 'z'.
11.	 Создайте строку '1-2-3-4-5-6-7-8-9' не используя цикл.
12.	Найдите сумму чисел от 1 до 100 не используя цикл.
13.	 Найдите произведение чисел от 1 до 10 не используя цикл.
14.	Даны два массива: первый с элементами 1, 2, 3, второй с элементами 'a', 'b', 'c'. Сделайте из них массив с элементами 1, 2, 3, 'a', 'b', 'c'.
15.	Дан массив с элементами 1, 2, 3, 4, 5. С помощью функции array_slice создайте из него массив $result с элементами 2, 3, 4.
16.	Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice преобразуйте массив в [1, 4, 5].
17.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice запишите в новый массив элементы [2, 3, 4].
18.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 2, 3, 'a', 'b', 'c', 4, 5].
19.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 'a', 'b', 2, 3, 4, 'c', 5, 'e'].
20.	 Дан массив 'a'=>1, 'b'=>2, 'c'=>3'. Запишите в массив $keys ключи из этого массива, а в $values – значения.
21.	 Даны два массива: ['a', 'b', 'c'] и [1, 2, 3]. Создайте с их помощью массив 'a'=>1, 'b'=>2, 'c'=>3'.
22.	Дан массив 'a'=>1, 'b'=>2, 'c'=>3. Поменяйте в нем местами ключи и значения.
23.	 Дан массив с элементами 1, 2, 3, 4, 5. Сделайте из него массив с элементами 5, 4, 3, 2, 1.
24.	Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-'.
25.	 Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-' и удалите его с помощью функции array_splice.
26.	Дан массив ['a', 'b', 'c', 'd', 'e']. Поменяйте элемент с ключом 0 на '!', а элемент с ключом 3 - на '!!'.
27.	Дан массив '3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b'. Попробуйте на нем различные типы сортировок.
28.	Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный ключ из данного массива.
29.	 Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный элемент данного массива.
30.	Дан массив $arr. Перемешайте его элементы в случайном порядке.
31.	 Заполните массив числами от 1 до 25 с помощью range, а затем перемешайте его элементы в случайном порядке.
32.	 Создайте массив, заполненный буквами от 'a' до 'z' так, чтобы буквы шли в случайном порядке и не повторялись.
33.	 Сделайте строку длиной 6 символов, состоящую из маленьких английских букв, расположенных в случайном порядке. Буквы не должны повторяться.
34.	Дан массив с элементами 'a', 'b', 'c', 'b', 'a'. Удалите из него повторяющиеся элементы.
35.	Дан массив с элементами 1, 2, 3, 4, 5. Выведите на экран его первый и последний элемент, причем так, чтобы в исходном массиве они исчезли.
36.	 Дан массив с элементами 1, 2, 3, 4, 5. Добавьте ему в начало элемент 0, а в конец - элемент 6.
37.	 Дан массив с элементами 1, 2, 3, 4, 5, 6, 7, 8. С помощью цикла и функций array_shift и array_pop выведите на экран его элементы в следующем порядке: 18273645. 
38.	 Дан массив с элементами 'a', 'b', 'c'. Сделайте из него массив с элементами 'a', 'b', 'c', '-', '-', '-'.
39.	 Заполните массив 10-ю буквами 'x'.
40.	 Создайте массив, заполненный целыми числами от 1 до 20. С помощью функции array_chunk разбейте этот массив на 5 подмассивов ([1, 2, 3, 4]; [5, 6, 7, 8] и т.д.).
1 задание
<?php
 $num = range(1, 100);
echo array_sum($num);
?>
<br>
<a href="#">2 задание</a><br>

<?php
$str = "'a','b','c','d','f'";
$str = strtoupper($str);
echo $str; 
?>

<br>
<a href="#">3 задание</a><br>
<?php
$arr = [1, 2, 3,4,5,6,7];
echo count($arr);
?>
<br>
<a href="#">4 задание</a><br>
<?php
$arr = [1, 2, 3, 4];
echo $arr[count($arr) - 1];
?>
<br>
<a href="#">5 задание</a><br>
<?php
$arr = [1, 2, 3, 4];
echo var_dump(in_array(2, $arr));
?>
<br>
<a href="#">6 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
echo array_sum($arr);
?>
<br>
<a href="#">7 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
echo array_product($arr);
?>
<br>
<a href="#">8 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
echo array_sum($arr) / count($arr);
?>
<br>
<a href="#">9 задание</a><br>
<?php
$num = range(1, 100);
echo print_r($num);
?>
<br>
<a href="#">10 задание</a><br>
<?php
$az = range('a', 'z');
echo print_r($az );
?>
<br>
<a href="#">11 задание</a><br>
<?php
$num = range(1, 9);
echo implode('-', $num);
?>
<br>
<a href="#">12 задание</a><br>
<?php
echo array_sum(range(1, 100));
?>
<br>
<a href="#">13 задание</a><br>
<?php
echo array_product(range(1, 10));
?>
<br>
<a href="#">14 задание</a><br>
<?php
$num = [1, 2, 3];
$az = ['a', 'b', 'c'];
var_dump(array_merge($num, $az));
?>
<br>
<a href="#">15 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
var_dump(array_slice($arr, 1, 3));
?>
<br>
<a href="#">16 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
var_dump(array_splice($arr, 1, 2));
?>
<br>
<a href="#">17 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
var_dump(array_splice($arr, 1, 3));
?>
<br>
<a href="#">18 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
var_dump(array_splice($arr, 3, 0, ['a', 'b', 'c']));
?>
<br>
<a href="#">19 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
$arr1 = array_splice($arr, 1, 0, ['a', 'b']);
$arr2 = array_splice($arr, 6, 0, ['c']);
$arr3 = array_splice($arr, 8, 0, ['e']);
echo print_r($arr1+$arr2+$arr3);
?>
<br>
<a href="#">20 задание</a><br>
<?php
$arr = ['a'=>1, 'b'=>2, 'c'=>3];
$keys = array_keys($arr);
$values = array_values($arr);
echo print_r($keys);
echo print_r($values);
?>
<br>
<a href="#">21 задание</a><br>
<?php
$arr1 = ['a', 'b', 'c'];
$arr2 = [1, 2, 3];
var_dump(array_combine($arr1, $arr2));
?>
<br>
<a href="#">22 задание</a><br>
<?php
$arr = ['a'=>1, 'b'=>2, 'c'=>3];
var_dump(array_flip($arr));
?>



<br>
<a href="#">23 задание</a><br>
<?php
var_dump(array_reverse([1, 2, 3, 4, 5]));
?>
<br>
<a href="#">24 задание</a><br>
<?php
$arr =  ['a', '-', 'b', '-', 'c', '-', 'd'];
$pos = array_search('-', $arr);
print_r($pos);
?>
<br>
<a href="#">25 задание</a><br>
<?php
$arr =  ['a', '-', 'b', '-', 'c', '-', 'd'];
$pos = array_search('-', $arr);
var_dump(array_splice($arr, $pos, 1));
print_r($arr);
?>

<br>
<a href="#">26 задание</a><br>
<?php
$arr =  ['a', 'b', 'c', 'd', 'e'];
var_dump(array_replace($arr, [0 => '!', 3 => '!!']));
print_r($arr);
?>

<br>
<a href="#">27 задание</a><br>
<?php
$arr = ['3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b'];
var_dump(sort($arr)); // по возрастанию 
var_dump(rsort($arr)); // по убыванию 
var_dump(ksort($arr)); // по возрастанию ключей
var_dump(krsort($arr)); // по убыванию ключей
?>

<br>
<a href="#">28 задание</a><br>
<?php
$arr = ['a'=>1, 'b'=>2, 'c'=>3];
echo $arr[array_rand($arr)];
?>

<br>
<a href="#">29 задание</a><br>
<?php
$arr = ['a'=>1, 'b'=>2, 'c'=>3];
echo array_rand($arr);
?>

<br>
<a href="#">30 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
var_dump(shuffle($arr));
print_r ($arr);
?>

<br>
<a href="#">31 задание</a><br>
<?php
$num = range(1, 25);
shuffle($num);
print_r ($num);
?>

<br>
<a href="#">32 задание</a><br>
<?php
$num = range('a', 'z');
shuffle($num);
print_r ($num);
?>

<br>
<a href="#">33 задание</a><br>
<?php
$characters = 'abcdefghijklmnopqrstuvwxyz';
echo substr(str_shuffle($characters), 0, 6);

?>

<br>
<a href="#">34 задание</a><br>
<?php
$az = ['a', 'b', 'c', 'b', 'a','c'];
$q  = var_dump(array_unique($az));
print_r ($q);
?>

<br>
<a href="#">35 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
echo array_shift($arr);
echo array_pop($arr);
?>
<br>
<a href="#">36 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5];
array_unshift($arr,0);
array_push($arr, 6);
print_r ($arr);
?>
<br>
<a href="#">37 задание</a><br>
<?php
$arr = [1, 2, 3, 4, 5, 6, 7, 8];
$str = '';
while (!empty($arr)) {
    $str .= array_shift($arr);
    $str .= array_pop($arr);
}
echo $str;
?>
<br>
<a href="#">38 задание</a><br>
<?php
$arr = ['a', 'b', 'c'];
$new = array_pad($arr, 6, '-');
print_r ($new);
?>
<br>
<a href="#">39 задание</a><br>
<?php
$arr = array_fill(0, 10, 'x');
print_r ($arr);
?>
<br>
<a href="#">40 задание</a><br>
<?php
$arr = range(1, 20);
$arr = array_chunk($arr, 4);
print_r ($arr);
?>



 <div class="heading">
 
</div>


   <h2 style="text-align: center">ВЫВОД</h2>
    PHP крайне прост для освоения, но вместе с тем способен удовлетворить запросы профессиональных программистов. Не пугайтесь длинного списка возможностей PHP. Вы можете быстро начать, и уже в течение нескольких часов сможете создавать простые PHP-скрипты.

Хотя PHP, главным образом, предназначен для работы в среде веб-серверов, область его применения не ограничивается только этим. Читайте дальше и не пропустите главу Возможности PHP либо, начните непосредственно с Вводного руководства, если вас интересует исключительно веб-программирование.
 
