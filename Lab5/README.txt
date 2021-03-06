Разработанная программа должна удовлетворять следующим требованиям:

Класс, коллекцией экземпляров которого управляет программа, должен реализовывать сортировку по умолчанию.
Для хранения необходимо использовать коллекцию типа java.util.TreeMap.
При запуске приложения коллекция должна автоматически заполняться значениями из файла.
Имя файла должно передаваться программе с помощью аргумента командной строки.
Данные должны храниться в файле в формате csv.
При остановке приложения текущее состояние коллекции должно автоматически сохраняться в файл.
Чтение данных из файла необходимо реализовать с помощью класса java.io.BufferedReader.
Запись данных в файл необходимо реализовать с помощью класса java.io.FileWriter.
Все реализованные команды (см. ниже) должны быть задокументированы в формате javadoc.
Формат задания объектов в командах - json.
В интерактивном режиме программа должна поддерживать выполнение следующих команд:

remove_lower {element}: удалить из коллекции все элементы, меньшие, чем заданный
remove_all {element}: удалить из коллекции все элементы, эквивалентные заданному
remove {String key}: удалить элемент из коллекции по его ключу
add_if_min {element}: добавить новый элемент в коллекцию, если его значение меньше, чем у наименьшего элемента этой коллекции
clear: очистить коллекцию
load: перечитать коллекцию из файла
info: вывести в стандартный поток вывода информацию о коллекции (тип, дата инициализации, количество элементов и т.д.)
