﻿https://github.com/okovtun/PV_224.git
https://www.youtube.com/watch?v=6V3cNxxigSc&list=PLeqyOOqxeiINRecRZn85PzuYkQg2vNipn
https://meet.google.com/mho-khdw-fhj

English:
https://www.newenglishfile.ru/

FreeBSD:
https://www.youtube.com/watch?v=AY8ZDMCinCQ&list=PLeqyOOqxeiINK1krBBk-nu_z52oubMPrO&index=62

////////////////////////////////////////////////////////////////////////////////////////////
////////////////////			   Standard Template Library			////////////////////
////////////////////////////////////////////////////////////////////////////////////////////

https://legacy.cplusplus.com/reference/stl/

TODO:
Создать std::list, проинициализировать его числами Фибоначчи, и добавить в него значение по индексу.
Индекс и значение вводятся с клавиатуры.

////////////////////////////////////////////////////////////////////////////////////////////
////////////////////					DATA CONTAINERS					////////////////////
////////////////////////////////////////////////////////////////////////////////////////////

TODO:
1. В класс Tree добавить следующие методы:
	??? minValue(???);			DONE
	??? maxValue(???);			DONE
	??? count(???);		//возвращает количество элементов дерева	DONE
	??? sum(???);				DONE
	??? avg(???);				DONE
	??? depth(???);		//возвращает глубину дерева			DONE
	??? erase(???);		//удаление элемента по значению		DONE
2. Обеспечить вызов всех методов без необходимости передачи корня дерева:	DONE
	Tree tree;
	for (int i = 0; i < n; i++)
	{
		tree.insert(rand() % 100);
	}
	tree.print();

DONE:
В ветке templated_list_2 шаблонизировать класс List
https://legacy.cplusplus.com/doc/tutorial/templates/#:~:text=Edit%20%26%20Run-,Class%20templates,-Just%20like%20we

DONE:
1. В класс List добавить метод ??? erase(???);
2. Написать operator+ и MoveMethods;
3. Проверочный код должен заработать:
	List list = { 3, 5, 8, 13, 21 };
	for(int i:list)
	{
		cout << i << tab;
	}
	cout << endl;

DONE:
В Solution DataContainers добавить проект List2 и в нем реализовать класс List, 
описывающий двусвязный список.

//										ForwardList

DONE:
1. Написать метод ??? reverse(???), который меняет порядок следования элементов на противоположный;	DONE
2. Проверочный код в секции RANGE_BASED_FOR_LIST должен заработать;-)

DONE:
1. В класс ForwardList добавить метод ??? erase(???), который удаляем элемент по указанному индексу;
2. В классе ForwardList написать деструктор таким образом, чтобы он удалял все элементы списка;
3. Проверочный код должен заработать:
	https://github.com/okovtun/PV_224/blob/96b5d54766ae6d15e4b92493129c7af371a2bcea/DataContainers/ForwardList/main.cpp#L184

////////////////////////////////////////////////////////////////////////////////////////////
////////////////////			INHERITANCE AND POLYMORPHISM			////////////////////
////////////////////////////////////////////////////////////////////////////////////////////

DONE:
В иерархии геометрических фигур расширить иерархию треугольников, Равнобедренным и прямоуголным треугольником.

DONE:
В иерархию геометрических фигур добавить Круг и Треугольник.
https://learn.microsoft.com/en-us/windows/win32/gdi/filled-shapes
https://learn.microsoft.com/en-us/windows/win32/gdi/about-ellipses
https://learn.microsoft.com/en-us/windows/win32/gdi/about-polygons

TODO:
Реализовать иерархию классов геометрических фигур: Квадрат, прямоугольник, треугольник, круг......
Для каждой фигуры необходимо выести ее первичные свойства (сторона квадрата, радиус круга....),
и вторичные свойства, такие как периметр, площадь, а так же каждую фигуру нужно нарисовать.

DONE:
1. Из файла 201 RAW.txt сделать новый файл 201 ready.txt, в котором столбики с IP и MAC адресами поменяны местами
	https://github.com/okovtun/PV_224/blob/master/Inheritance/FilesTask/201%20RAW.txt
2. Из файла 201 RAW.txt сделать новый файл 201.dhcpd, следующего формата:
	https://github.com/okovtun/PV_224/blob/master/Inheritance/FilesTask/201.dhcpd

DONE:
1. Сохранить группу в файл;		DONE
2. Загрузить группу из файла;	DONE

DONE:
1. Проработать dynamic_cast;
2. Оптимизировать перегрузку операторов вывода таким образом, 
   чтобы необходимости в dynamic_cast небыло;

DONE:
В проект Academy добавить класс Graduate, который описывает дипломника.

TODO:
Скомпилировать проект String в *.lib-файл, и проверить этот *.lib-файл в другом проекте.

DONE:
В классе String реализовать MoveMethods;
https://cplusplus.com/doc/tutorial/classes2/
https://en.cppreference.com/w/cpp/language/rule_of_three

DONE:
1. В классе Fraction перегрузить оператор ввода:		DONE
	Fraction A;
	cout << "Введите простую дробь: "; cin >> A;
	cout << A << endl;
2. Проверочный код должен заработать:					DONE
	https://github.com/okovtun/PV_224/blob/398ca6279a92adfe0a564cf58b16beb3a9c93180/IntroductionToOOP/String/main.cpp#L94;

DONE:
Проверочный код в секции CONVERSION_FROM_CLASS_TO_OTHER_TYPES должен заработать.

DONE:
Для класса Fraction перегрузить:
1. Составные присваивания: +=, -=, *=, /=;		DONE
2. Операторы сравнения: ==, !=, >, <, >=, <=;
3. Написать метод reduce(), который сокращает дробь;
	https://www.webmath.ru/poleznoe/formules_12_7.php

DONE:
0. Выучить теорию!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
1. Реализовать класс Fraction, описывающий простую дробь.
   В классе должны быть все необходимые методы, так же нужно обеспечить
   выполнение арифметических и других важных операций над дробями;

DONE:
0. Выучить теорию!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
1. Написать метод ??? distance(???) который возвращает расстояние до указанной точки;	DONE
2. Написать функцию ??? distance(???) которая возвращает расстояние между двумя точками;

DONE:
1. *В класс Point добавить get/set-методы.