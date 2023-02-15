# Контрольная работа
## Список задач:
1. Создать репозиторий на GitHub
2.Нарисовать блок схему алгоритма
3. Снабдить репозиторий оформленным текстовым описанием (файл Readмe.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этап 2, 3 и 4 должны быть расположены в разных коммитах)

## Решение:
1. Репозиторий на GitHub: https://github.com/Ayrplan/Kontr.Work.git
2. Блок-схема: 
![Это блок-схема](2023-02-14_12-10-56.jpg)
3. Файл Readme.md: https://github.com/Ayrplan/Kontr.Work/blob/main/Readme.md
4. Решение задачи: https://github.com/Ayrplan/Kontr.Work/blob/main/Program.cs
* Ввод данных массива и формирования массива строк происходит с участием разделителя между элементами ", "
* Оператором является .Split.

* Console.Write("Введите данные массива через',': ");
* string strLine = Console.ReadLine();
* string[] inArr = strLine.Split(", ");
* string[] outArr = new  string[0];   
* resultJoin = string.Join(",", inArr); 
5. Коммиты: https://github.com/Ayrplan/Kontr.Work/commits/main