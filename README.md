# Torrent Manager
MVP v. 0.0.8
#### Наша группа в Telegram: https://t.me/btt_manager

+ [Как использовать скрипт](#info);
+ [Как заработать больше](#money);
+ [Вывод на Binance](#binance);
+ [Как безопасно качать файлы](#QBittorrent).

_**Donate:**_
- TRX/BTT: _**TSyujStera3SMSxuntzqAaf5y4SBzwnm23**_
- VISA SBERBANK: _**4274 3200 4502 9926**_

<a name="info">Как использовать скрипт</a>
-------------------------
На сегодняшний день поддержка BTT есть только у клиентов μTorrent/BitTorrent последних версий.
Для увеличения шанса получения BTT необходимо ограничить количество других клиентов.
Данный скрипт блокирует другие клиенты по их названию и версии.
Инструкция по использованию:

1. Качаем и устанавливаем NodeJS версию LTS: https://nodejs.org/ru/
2. Качаете [этот репозиторий](https://github.com/aliasxrus/torrent-manager) (Если нет гита то нажимаете сверху кнопку Code и выбираете Download zip, затем извлекаете и переходите в папку).
3. В торрент клиенте открываете _**настройки -> дополнительно -> веб интерфейс**_, указываете логин, пароль и порт (придумать самим, порт лучше в диапазоне от 20000 до 60000). 
4. Находите среди файлов скрипта _**config.js**_ и открываете в любом текстовом редакторе, заполняете поля как в пункте выше. Удобнее всего редактировать через [Notepad++](https://notepad-plus-plus.org/downloads/)
5. Для запуска программы используйте _**START.bat**_

Инструкция от @Sandra2Z для старой версии https://telegra.ph/Kak-zapustit-skript-ot-Kharis-Shamsuarov-cherez-komandnuyu-stroku-04-25
    
Это просто демонстрация, нормальная версия будет чуть позже. Тут куча багов и ошибок!!!

<a name="money">Как заработать больше</a>
-------------------------
Самый простой способ заработка это увеличить количество раздающих компьютеров.
При желании можно взять _**[VPS](https://zomro.com/vds.html?from=294244)**_ в аренду, проверенные виртуальные сервера можно арендовать на _**[ZOMRO](https://zomro.com/vds.html?from=294244)**_.
Рекомендую тариф _**VDS/VPS «MEGA»**_ c SSD до 100Gb с операционной системой Windows. Средний срок окупаемости до недели. Для более стабильной работы торрент клиента лучше использовать Windows-Server-2012-R2-RUS.

Протестированные VPS:
- _**[FirstByte](https://firstbyte.ru/?from=80394)**_

<a name="binance">Вывод на Binance</a>
-------------------------
Первым делом регистрируемся на _**[Binance](https://www.binance.com/ru/register?ref=140122449)**_.
Для возможности перевода на кошелек нужно:
   - перечисляем на кошелек в торрент клиенте 0.1 TRX. Их можно купить на _**[Binance](https://www.binance.com/ru/register?ref=140122449)**_ или попросить в профильных чатах, к примеру https://t.me/BTTBitTorrentRU
   - адрес вашего кошелька указан в _**Кошелек -> Публичный адрес**_ (в правом верхнем углу 3 точки, сразу после "Информация по восстановлению данных")
   - если у вас несколько кошельков BTT, то нужно перевести TRX только на 1 из них. При первом переводе на _**[Binance](https://www.binance.com/ru/register?ref=140122449)**_ он активирует ваш TRX/BTT кошелек на бинансе и можно будет переводить с любых BTT кошельков с торрент клиента.

Перевод на кошелек _**[Binance](https://www.binance.com/ru/register?ref=140122449)**_
   - первым делом необходимо перевести баланс из _**BTT in-app**_ в _**BTT on-chain**_. Это занимает некоторое времени, результат можно посмотреть в _**История**_
   - кошелек бинанса можно найти в _**Кошелек -> Обзор кошелька -> Основной аккаунт**_, тут находим _**BTT**_ через _**Поиск монет**_ и в колонке _**Действие**_ нажимаем кнопку _**Ввод**_.
   - в правой части окна указан ваш кошелек, проверяем что выбран TRC20 и копируем кошелек.
   - далее переводим _**BTT on-chain**_ на бинанс. Для этого в выпадающем меню выбираем _**Другой публичный адрес**_ куда вводим BTT кошелек с бинанса.

Вывод денег на банковскую карту:
   - переходим на _**[BestChange](https://www.bestchange.ru/?p=1226003)**_, сразу под логотипом переходим в _**Список**_ и выбираете что отдаёте BTT и куда собираетесь принять средства. Нажимаем _**Найти лучший курс**_.
   - сайт подберет лучшие по курсу обменники и предложит их на выбор.
   - переходим на обменник, заполняем необходимые поля.
   - переводим с _**[Binance](https://www.binance.com/ru/register?ref=140122449)**_ кошелька _**Кошелек -> Обзор кошелька -> Основной аккаунт**_, тут находим _**BTT**_ через _**Поиск монет**_ и в колонке _**Действие**_ нажимаем кнопку _**Вывод**_.
   - переводим на кошелек обменника и ждём поступления денег.

<a name="QBittorrent">Как качать файлы не теряя BTT</a>	
-------------------------
При скачивании файлов есть опасность потратить свои BTT, они будут потрачены на ускорение скачивания.
Для предотвращения этого можно скачивать торрент другим клиентом и в автоматическом режиме передавать их в μTorrent/BitTorrent.
1. Скачиваем и устанавливаем [QBittorrent](https://www.qbittorrent.org/download.php)
2. Переходим в настройки QBittorrent: Сервис -> Настройки... -> Загрузки
    - указываем _**Путь сохранения по умолчанию**_, это папка куда будут скачиваться торренты. 
    - указываем _**Копировать торрент-файлы завершенных загрузок в**_, сюда будут сохранены торрент файлы для передачи их в μTorrent/BitTorrent.
3. Переходим в настройки QBittorrent: Сервис -> Настройки... -> BitTorrent
   - В самом низу находим _**Ограничения раздачи**_
   - Ставим галку _**По достижению рейтинга раздачи**_ в значение: 0
   - В пункте _**затем**_ выбираем _**Остановить торрент**_
4. Заходим в μTorrent Настройки -> Настройки программы
   - указываем путь _**Помещать загружаемые файлы в**_ как у QBittorrent.
   - ставим галку у пункта _**Automatically load torrents from**_ и указываем путь куда QBittorrent сохраняет торрент файлы.