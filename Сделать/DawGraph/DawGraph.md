Название получилось от совмещения двух слов: dawg и graph.
Проект будет показывать на графике даты стримов давга и ко., и их названия.
График можно фильтровать по определённому стримеру.
Бэкенд хочу сделать на Rust, чтобы прокачать навык.
Фронт на Quasar, потому что круто.

Админ цифры предоставил json бекап таблицы со списком всех стримов, вместе с [[Описание структуры бд|описанием структуры таблицы]], за что ему нижайшее благодарен.

Выдал ему sftp доступы на сервер:
IP - `5.167.135.102`
Или host - `sftp.sumax.ru`
port - `8000`
user - `cifra`
password - `g2Bh12jZ3@@#`
Папка - `/home/cifra/backups`

Возможно, бекапы будут закачивать туда автоматически

Попробую сделать несколько сервисов. Один на **загрузку json бекапа в mysql**, второй для **выдачи данных** фронтовому приложению.

