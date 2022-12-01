# bntu.vsrpp.vmisyakova
Lab01 по дисциплине "Визуальные средства разработки программных приложений. XMLParser.
Необходимо прочитать выбранный пользователем xml-файл простой структуры (список объектов) и вывести колчиество данных объектов в файле на экран. Предоставить пользователю возможность выполнения слудющих операций над прочитанными данными:
-	Максимлаьное значение;
-	Минимлаьное значение;
-	Среднее;
-	Средняя длина строки;
-	Минимальная длина строки;
-	Максимальная длина строки.
При выборе пользователем операции, необходимо выводить список параметров объекта для которых данная операци возможна. После выбора параметра - выводить результат ранее выбранной операции. Параметр может быть в списке доступных, только если он существует у всех объектах, а также имеет одинаковый тип (например параметр score - во всех объектах определен как число). По желанию пользователю необходимо привести объекты в xml документе к единому виду. Т.е. выполнить следующий алгоритм:
1.	Если у элемента имеется дочерний элемент с именем FIO или FullName, то необходимо разбить данный элемент на отдельные элементы с именами: FirstName, LastName, Surname;
2.	Создать недостающие дочерние элементы в объектах, для строк указать значение N/A, для числовых элементов - 0;
3.	Полученный результат записать в файл с именем <имя исходного файла>_output.xml.
Lab02 по дисциплине "Визуальные средства разработки программных приложений. Currency converter.
1.	Программа должна использовать в своей работе официальные курсы валют взятые с сайта Национального Банка Республики Беларусь.
2.	Пользователь должен иметь возможность просматривать курсы всех доступных валют
3.	Программа должна предоставлять пользователю возможность проводить конвертации типа: BYN -> валюта, валюта -> BYN, валюта->валюта (конвертация через BYN)
4.	По желанию пользователя небоходимо построить график изменения курса за выбранный период, а также определить дату, когда курс был минимальный/максимальный и средний арифметический курс за тот же период.




