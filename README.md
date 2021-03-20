## Постановка задачи 
Модель «Отдел кадров» должна содержать информацию о сотрудниках, подразделениях организации, должностях, официальных документах (паспорт, диплом, военный билет и т.п.)
# Задачи:
•	Построить E-R диаграмму средствами AllFusion Data Modeler (ERwin) и сформулировать запросы на языке реляционной алгебры.</>
• получить список всех сотрудников, работающих в заданном подразделении;</>
• получить список сотрудников, работающих под руководством того же начальника, что и у выбранного сотрудника;</>
• получить список всех однофамильцев заданного начальника подразделения;</>
• для заданного подразделения получить пары (Ф.И.О. сотрудника, № военного билета), сотрудников, работающих в заданной должности;</>
• получить список всех подразделений, в которых работают сотрудники с ученой степенью (на основании диплома);</>
• получить список сотрудников, состоящий из троек (Ф.И.О. сотрудника, № паспорта, должность), пенсионного возраста. (Обратить внимание на то, что у мужчин и женщин пенсионный возраст разный).</>

# Реализовать смоделированную базу данных и выполнить следующие задачи:

Задача 1. Создать базу данных, спроектированную в ходе выполнения предыдущей практической работы, в любой SQL среде 
Задача 2. Предусмотреть триггеры, пересчитывающие значение вычислимого атрибута, где это необходимо (исходя из бизнес-правил задания) 
Задача 3. Импортировать и экспортировать данные в созданную базу с использованием средств служб DTS и языка SQL: 
a. с помощью SQL-команды (например, BULK INSERT или OPENROWSET (BULK...) для MS SQL; COPY для Postgres SQL или прочее); 
b. с помощью мастера импорта и экспорта. 
Задача 4. Сформировать запросы к построенной базе данных информационной системы в соответствии с выбранной моделью и заданием №2 предыдущей практической работы 
Задача 5. Создать хранимую процедуру по внесению новой записи в любое отношение 
Задача 6. Создать набор пользователей БД и разграничение прав доступа к объектам БД для разных пользователей (минимально 3 пользователя с разными правами) 
Задача 7. Настроить шифрование любого атрибута. Создать представление, возвращающее данные в расшифрованном виде. Предусмотреть ограниченный доступ к этому представлению 
Задача 8. Создать резервную копию БД, удалить ее и восстановить БД по резервной копии 
Задача 9. Подготовить и загрузить отчет о выполнении практической работы в Google Classroom
