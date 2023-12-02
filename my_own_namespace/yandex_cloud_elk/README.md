# Ansible Collection - my_own_namespace.yandex_cloud_elk

Documentation for the collection.

В коллекции представлены:
Модуль ```my_own_module``` создает файл с указаным названием и содержимым.
Переменные в модуле:
```path``` - путь и название создаваемого файла
```content``` - содержимое файла, который будет создан в ```path```

Роль ```my_own_module_role``` предназначена для проверки модуля и включает task с заданными переменными:
```default_path``` - передает значение ```path``` в модуль ```my_own_module```, по-умолчанию создается файл ```./file.txt``` в текущем каталоге.
```default_content``` - передает значение ```content``` в модуль ```my_own_module```, по-умолчанию содержит: ```Content for the file in the path variable```