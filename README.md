<p align="center">
  <img src="img/logo.png" width="96" alt="JamalBim">
</p>

<h1 align="center">JamalBim</h1>

<p align="center">
  Плагин для Revit 2025, 2026 и 2027. Отопление, тёплый пол, спецификации, семейства.<br>
  Бесплатно.
</p>

<p align="center">
  <a href="https://github.com/jona-06/JamalBim/releases/latest/download/JamalBim.exe"><img src="https://img.shields.io/badge/Скачать-JamalBim.exe-2ea44f?style=for-the-badge" alt="Скачать JamalBim.exe"></a>
  <a href="https://t.me/jamalbim"><img src="https://img.shields.io/badge/Telegram-канал-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

Большую часть этих инструментов я сначала делал для своих проектов ОВ и ВК: чтобы не раскладывать тёплый пол руками, не считать теплопотери в Excel и не чистить семейства перед сдачей. Со временем из них собрался JamalBim.

После установки в Revit появляется вкладка **JamalBim**. Обновления приходят сами: в трее висит значок, он сообщает о новой версии и ставит её. Любой инструмент можно отключить, если он вам не нужен.

## Как установить

1. Скачать [JamalBim.exe](https://github.com/jona-06/JamalBim/releases/latest/download/JamalBim.exe).
2. Запустить и отметить свои версии Revit.
3. Открыть Revit.

## Что внутри

**Отопление**

| | | |
|---|---|---|
| <img src="img/icons/smart_loop_64.png" width="32"> | **Умный контур** | Раскладывает петли тёплого пола по помещениям: улитка, змейка, обход колонн. Старается сделать петли одной длины |
| <img src="img/icons/heat_loss_64.png" width="32"> | **Расчёт теплопотерь** | Теплопотери помещений по СП 50.13330, 60.13330 и 131.13330 |

**Утилиты**

| | | |
|---|---|---|
| <img src="img/icons/converter_64.png" width="32"> | **Быстрый расчёт** | Подбор трубы, Kvs, мощность и расход, радиатор на свой график, тёплый пол по пирогу, смесительный узел, расширительный бак, воздуховоды. Плюс конвертер единиц |
| <img src="img/icons/hookup_64.png" width="32"> | **Схема обвязки** | Собирает схему обвязки узла, взрыв-схему и спецификацию к ней |
| <img src="img/icons/clash_check_64.png" width="32"> | **Проверка пересечений** | Ищет коллизии на открытом виде |
| <img src="img/icons/sheet_export_64.png" width="32"> | **Экспорт листов** | Листы и виды в PDF, DWG и IFC: свои имена файлов, папки, архив ZIP |
| <img src="img/icons/importer_64.png" width="32"> | **Импортер** | Вставляет таблицу из Excel, чата или JSON в спецификацию по ГОСТ |

**Данные**

| | | |
|---|---|---|
| <img src="img/icons/family_manager_64.png" width="32"> | **Менеджер семейств** | Показывает, какие семейства есть в проекте и где они стоят. Можно удалить лишнее или заменить одно другим сразу во всём проекте |
| <img src="img/icons/lookup_table_64.png" width="32"> | **Таблицы выбора** | Редактор Lookup Tables для семейств, без возни с CSV |
| <img src="img/icons/specification_64.png" width="32"> | **Категории семейств** | Раскладывает элементы по категориям для спецификаций |
| <img src="img/icons/updater_64.png" width="32"> | **Апдейтер** | Заполняет ADSK_Наименование и количество, можно пакетно |
| <img src="img/icons/dummy_families_64.png" width="32"> | **Пустышки** | Хомуты, гайки, датчики и прочее, что нужно в спецификации, но не нужно в модели. Создаются списком из таблицы |

**Вид**

| | | |
|---|---|---|
| <img src="img/icons/walk_3d_64.png" width="32"> | **Прогулка 3D** | Ходишь по модели как в игре, на WASD и мышке. По лестницам поднимается плавно |
| <img src="img/icons/node_sheets_64.png" width="32"> | **Развёртка пространств** | Одной кнопкой делает лист узла: кусок плана, развёртку стен и аксонометрию помещения |

## Связь

Видео, новости и вопросы — в Telegram: [t.me/jamalbim](https://t.me/jamalbim).

Если что-то сломалось или есть идея, пишите в [Issues](https://github.com/jona-06/JamalBim/issues) или в канал.

<sub>Плагин бесплатный, исходники не публикую. Autodesk и Revit — товарные знаки Autodesk, Inc.</sub>
