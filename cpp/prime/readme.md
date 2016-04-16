<h3>Оглавление</h3>
<a href="#one">1. Задача</a><br>
<a href="#two">&nbsp;&nbsp;&nbsp;1.1. Пример работы</a><br>
<a href="#three">2. Теория</a><br>
<a href="#four">&nbsp;&nbsp;&nbsp;2.1. Простое число</a><br>
<a href="#five">&nbsp;&nbsp;&nbsp;2.2. Тесты просты</a><br>
<!--

<a href="#five">&nbsp;&nbsp;&nbsp;1.4. Определитель матрицы</a><br>
<a href="#six">&nbsp;&nbsp;&nbsp;1.5. Транспонирование</a><br>
<a href="#seven">&nbsp;&nbsp;&nbsp;1.6. Обратная матрица</a><br>

-->

<h3 id="one">1. Задача: определить является ли число простым</h3>
<p>Вопрос определения того, является ли натуральное число N простым, известен как проблема простоты. Тестом простоты (или проверкой простоты) называется алгоритм, который, приняв на входе число N, позволяет либо не подтвердить предположение о составности числа, либо точно утверждать его простоту. Во втором случае он называется истинным тестом простоты. Таким образом, тест простоты представляет собой только гипотезу о том, что если алгоритм не подтвердил предположение о составности числа N, то это число может являться простым с определенной вероятностью.</p>

<b id="two">1.1. Пример работы</b> <br> <br>

<h3 id="three">2. Теория</h3>
<b id="four">2.1. Простое число</b>
<p>Просто́е число́ — натуральное (целое положительное) число, имеющее ровно два различных натуральных делителя — единицу и самого себя. Другими словами, число p является простым, если оно больше 1 и при этом делится без остатка только на 1 и на p (на самого себя).</p>

<p>
	Пример: 5 простое число, потому что делится только на 1 и на 5, а 6 является составным числом, так как делится на 2 и 3, помимо 1 и 6.
</p>

<p>
	Натуральные числа, бо́льшие единицы, не являющиеся простыми, называются составными. Таким образом, все натуральные числа разбиваются на три класса: единицу (имеющую один натуральный делитель), простые числа (имеющие два натуральных делителя) и составные числа (имеющие больше двух натуральных делителей). Основная теорема арифметики утверждает, что каждое натуральное число, большее единицы, представимо в виде произведения простых чисел, причём единственным способом с точностью до порядка следования сомножителей. Таким образом, простые числа являются элементарными «строительными блоками» натуральных чисел.
</p>


<b id="five">2.2. Тесты простоты</b>
<p>Существующие алгоритмы проверки числа на простоту могут быть разделены на две категории: истинные тесты простоты и вероятностные тесты простоты. Истинные тесты результатом вычислений всегда выдают факт простоты либо составности числа, вероятностный тест дает ответ о составности числа либо его несоставности с некоторой вероятностью. Если сказать проще, то вероятностный алгоритм говорит, что число скорее всего не является составным, однако в итоге оно может оказаться как простым, так и составным. Числа, удовлетворяющие вероятностному тесту простоты, но являющиеся составными, называются псевдопростыми. </p>

<p>
	На практике вместо получения списка простых чисел зачастую требуется проверить, является ли данное число простым. Алгоритмы, решающие эту задачу, называются тестами простоты. Существует множество полиномиальных тестов простоты, но большинство их являются вероятностными (например, тест Миллера — Рабина) и используются для нужд криптографии. В 2002 году было доказано, что задача проверки на простоту в общем виде полиномиально разрешима, но предложенный детерминированный тест Агравала — Каяла — Саксены имеет довольно большую вычислительную сложность, что затрудняет его практическое применение.
</p>