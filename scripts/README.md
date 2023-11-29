# Встановлення плагіну
Щоб почати використовувати скріпт `kubeplugin` як плагін кубернетіс виконайте наступне

Перемістіть виконуваний файл у будь-яке місце на вашому PATH.
Наприлад за допомогою команди ```cp kubeplugin <dir in path>/kubectl-resources-usage```

Важливо ```<resources-usage>``` це буде ваша команда для запуску плагіна, за бажанням можна використати іншу

Перевірити доступність плагіна ```kubectl resources usage```. 

# Використання плагіну
Плагін приймає 2 аргументи, такі як resource і namespace

```kubectl resources usage pod kube-system```