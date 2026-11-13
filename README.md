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

<table>
<tr><td width="56" align="center"><img src="img/icons/smart_loop_64.png" width="40" height="40"></td><td width="190"><b>Умный контур</b></td><td>Раскладывает петли тёплого пола по помещениям: улитка, змейка, обход колонн. Старается сделать петли одной длины</td></tr>
<tr><td width="56" align="center"><img src="img/icons/heat_loss_64.png" width="40" height="40"></td><td width="190"><b>Расчёт теплопотерь</b></td><td>Теплопотери помещений по СП 50.13330, 60.13330 и 131.13330</td></tr>
</table>

**Утилиты**

<table>
<tr><td width="56" align="center"><img src="img/icons/converter_64.png" width="40" height="40"></td><td width="190"><b>Быстрый расчёт</b></td><td>Подбор трубы, Kvs, мощность и расход, радиатор на свой график, тёплый пол по пирогу, смесительный узел, расширительный бак, воздуховоды. Плюс конвертер единиц</td></tr>
<tr><td width="56" align="center"><img src="img/icons/hookup_64.png" width="40" height="40"></td><td width="190"><b>Схема обвязки</b></td><td>Собирает схему обвязки узла, взрыв-схему и спецификацию к ней</td></tr>
<tr><td width="56" align="center"><img src="img/icons/clash_check_64.png" width="40" height="40"></td><td width="190"><b>Проверка пересечений</b></td><td>Ищет коллизии на открытом виде</td></tr>
<tr><td width="56" align="center"><img src="img/icons/sheet_export_64.png" width="40" height="40"></td><td width="190"><b>Экспорт листов</b></td><td>Листы и виды в PDF, DWG и IFC: свои имена файлов, папки, архив ZIP</td></tr>
<tr><td width="56" align="center"><img src="img/icons/importer_64.png" width="40" height="40"></td><td width="190"><b>Импортер</b></td><td>Вставляет таблицу из Excel, чата или JSON в спецификацию по ГОСТ</td></tr>
</table>

**Данные**

<table>
<tr><td width="56" align="center"><img src="img/icons/family_manager_64.png" width="40" height="40"></td><td width="190"><b>Менеджер семейств</b></td><td>Показывает, какие семейства есть в проекте и где они стоят. Можно удалить лишнее или заменить одно другим сразу во всём проекте</td></tr>
<tr><td width="56" align="center"><img src="img/icons/lookup_table_64.png" width="40" height="40"></td><td width="190"><b>Таблицы выбора</b></td><td>Редактор Lookup Tables для семейств, без возни с CSV</td></tr>
<tr><td width="56" align="center"><img src="img/icons/specification_64.png" width="40" height="40"></td><td width="190"><b>Категории семейств</b></td><td>Раскладывает элементы по категориям для спецификаций</td></tr>
<tr><td width="56" align="center"><img src="img/icons/updater_64.png" width="40" height="40"></td><td width="190"><b>Апдейтер</b></td><td>Заполняет ADSK_Наименование и количество, можно пакетно</td></tr>
<tr><td width="56" align="center"><img src="img/icons/dummy_families_64.png" width="40" height="40"></td><td width="190"><b>Пустышки</b></td><td>Хомуты, гайки, датчики и прочее, что нужно в спецификации, но не нужно в модели. Создаются списком из таблицы</td></tr>
</table>

**Вид**

<table>
<tr><td width="56" align="center"><img src="img/icons/walk_3d_64.png" width="40" height="40"></td><td width="190"><b>Прогулка 3D</b></td><td>Ходишь по модели как в игре, на WASD и мышке. По лестницам поднимается плавно</td></tr>
<tr><td width="56" align="center"><img src="img/icons/node_sheets_64.png" width="40" height="40"></td><td width="190"><b>Развёртка пространств</b></td><td>Одной кнопкой делает лист узла: кусок плана, развёртку стен и аксонометрию помещения</td></tr>
</table>

## Связь

Видео, новости и вопросы — в Telegram: [t.me/jamalbim](https://t.me/jamalbim).

Если что-то сломалось или есть идея, пишите в [Issues](https://github.com/jona-06/JamalBim/issues) или в канал.

<sub>Плагин бесплатный, исходники не публикую. Autodesk и Revit — товарные знаки Autodesk, Inc.</sub>
