##Задача – «Жесткий диск»

### Написать программу, имитирующую работу файловой системы.

Файлы и метаданные должны храниться на "жестком диске".

Файл имеет имя и блок с данными.

"Жесткий диск" представлен в памяти как массив байт фиксированного размера.

Для упрощения будем считать:
* Размер файла не превышает 10 байт;
* Количество файлов не превышает 100_000;
* Имя файла не длиннее 50 символов;

Требуется реализовать api:
* Создание файла;
* Удаление файла по имени.
