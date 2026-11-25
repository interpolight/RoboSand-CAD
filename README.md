# RoboSand — двухколёсный ровер

RoboSand — проект простейшего ровера с корпусом для 3D-печати. Два шаговых двигателя NEMA 17 независимо вращают колёса Ø90 × 32 мм. Ровер поворачивает за счёт разницы скоростей колёс. Сзади шасси поддерживает шаровая опора CY-15A высотой 25 мм.

Под съёмной крышкой находятся плата MKS DLC32 V2.1, два драйвера TMC2209 и аккумуляторная кассета на четыре элемента 18650. Чтобы увидеть компоновку и проводку в FreeCAD, выберите крышку в дереве модели и нажмите пробел. [Сборка FreeCAD](RoboSand_Rover_17HS19_Light.FCStd) · [Файлы для печати](STL/)

## Ведомость изделий (BOM)

Ниже указаны количества на один ровер. В HTML-ведомости можно задать размер партии, рассчитать закупку с учётом фасовки и скачать STL. На странице файла нажмите **Download raw file** и откройте сохранённый HTML в браузере. [Ведомость в HTML](RoboSand_BOM.html)

### Печатные детали

Для одного ровера нужны девять деталей из семи STL. Модели ориентированы для печати в масштабе 100 %. Колесо и ступицу напечатайте по два раза. Ступица рассчитана на вал Ø5 мм с лыской.

| Деталь и файл STL | Материал | Количество |
| --- | --- | ---: |
| [Перфорированный корпус](STL/01_Hull_PETG.stl) | PETG | 1 |
| [Съёмная крышка с перфорацией](STL/02_Lid_PETG.stl) | PETG | 1 |
| [Кассета для держателя 4 × 18650](STL/03_Battery_tray_PETG.stl) | PETG | 1 |
| [Площадка шаровой опоры H25](STL/04_Caster_mount_PETG_H25.stl) | PETG | 1 |
| [Ведущее колесо](STL/05_Wheel_TPU_95A_x2.stl) | TPU 95A | 2 |
| [Разрезная втулка кабеля питания](STL/06_Cable_grommet_TPU.stl) | TPU | 1 |
| [Ступица под вал с лыской](STL/07_Hub_PETG_CF_x2.stl) | PETG-CF | 2 |

### Покупные детали

| Изделие | На один ровер | Карточка товара |
| --- | ---: | --- |
| Шаговый двигатель NEMA 17, StepperOnline 17HS19-2004S1 | 2 шт. | [StepperOnline](https://www.omc-stepperonline.com/nema-17-bipolar-59ncm-84oz-in-2a-42x48mm-4-wires-w-1m-cable-connector-17hs19-2004s1) |
| Шаровая опора, CY-15A | 1 шт. | [Амперкот](https://amperkot.ru/products/koleso_dlya_robota_cy15a/39176892.html) |
| Плата управления с Wi-Fi, MKS DLC32 V2.1 | 1 шт. | [Амперкот](https://amperkot.ru/products/plata_kontrollera_graverom__cnc_mks_dlc32_v21_na_baze_esp32/40620693.html) |
| Драйвер с радиатором, MKS TMC2209 | 2 шт. | [Амперкот](https://amperkot.ru/products/drayver_shagovogo_dvigatelya_mks_tmc2209_2a_47528v_s_radiatorom/41259961.html) |
| Антенна Wi-Fi с кабелем IPX, AntennaHome AH2G.207 | 1 шт. | [Амперкот](https://amperkot.ru/products/pcb_antenna_antennahome_fpc3710__24_58_ggts____ah2g207_25_40_dbi/41231864.html) |
| Держатель 4 × 18650 с выводами, Амперка AMP-X789 | 1 шт. | [Амперка](https://amperka.ru/product/battery-holder-4x18650) |
| Аккумулятор Li-ion 18650, LG Chem LGDBHE41865 · AMP-X541 | 4 шт. | [Амперка](https://amperka.ru/product/battery-li-ion-18650-rechargeable) |
| Разъём для съёмной кассеты, Amass XT30U-MF · CON017 | 1 пара | [ОсколЧип](https://oskolchip.ru/shop/511/desc/xt30-razem-silovoj-pitanija-para-mama-papa-xt30-m-xt30-p) |
| Угловой штекер DC с проводом, 5,5 × 2,1 мм · 18-0083 | 1 шт. | [Alee Market](https://aleemarket.ru/5521-shteker-pitaniya-dc-uglovoy-s-provodom--30sm--pryamoy/) |
| Термоусадка для хвостовиков XT30U, СТТК 3:1 · Ø4,8/1,6 мм | 60 мм | [КабельГарант](https://kabelgarant.ru/termousadochnaya-trubka-kleevaya-4816-mm-prozrachnaya-1-m/) |
| Многоразовая лента для ремешка, AIRLINE ADTV001 · 10 × 1 мм | 250 мм | [AIRLINE](https://airline.su/catalogue/avtoaksessuary/khomuty-kley-izolenta-styazhki-plomby/lenty-na-kleevoy-osnove-izolenta-skotch-plyenka/izolenty-dlya-zhgutirovaniya/lenta-lipuchka-dlya-styazhki-zhgutirovaniya-kabeley-10mm-5m-chernaya-adtv001/) |

При расчёте заказа HTML-ведомость учитывает два двигателя из запаса. Если собираете ровер с нуля, берите количество из графы «На одного». Плату защиты 4S и зарядное устройство для выбранных ячеек ещё предстоит подобрать.

### Крепёж

| Изделие | На один ровер | Карточка товара |
| --- | ---: | --- |
| Винт M3 × 8, DIN 912 | 8 шт. | [Robot-Kit](https://robot-kit.ru/Metric-Head-Screw-12M3X8ST/) |
| Винт M3 × 10, DIN 912 | 2 шт. | [Robot-Kit](https://robot-kit.ru/metric-head-screw-DIN-912-M3X10H/) |
| Винт M3 × 12, DIN 912 | 8 шт. | [Robot-Kit](https://robot-kit.ru/Metric-Head-Screw-12M3X12ST/) |
| Установочный винт M3 × 10, DIN 913 | 2 шт. | [23 Болта](https://23bolta.ru/product/vint-ustanovochnyy-nerzhaveyuschiy-3h10-din913-guzhon-card/) |
| Винт M3 × 14, DIN 912 | 2 шт. | [Robot-Kit](https://robot-kit.ru/Metric-Head-Screw-12M3X14ST/) |
| Винт M4 × 10, DIN 912 | 2 шт. | [Robot-Kit](https://robot-kit.ru/2133/) |
| Гайка шестигранная M3, DIN 934 | 14 шт. | [Бауцентр](https://baucenter.ru/product/gayka-shestigrannaya-m3-20-sht-din934-otsinkovannaya-fixberg-ctg-29320-29321-32408-720008400/) |
| Гайка шестигранная M4, DIN 934 | 2 шт. | [Robot-Kit](https://robot-kit.ru/DIN-934-M4-10/) |
| Шайба плоская M3, DIN 125 A, 3,2 × 7 × 0,5 мм | 8 шт. | [Бауцентр](https://baucenter.ru/product/shayba-ploskaya-din-125a-otsinkovannaya-m3-40-sht-ctg-32417-720008399/) |
| Винт для термопласта 3 × 6, Bossard BN 13577 | 4 шт. | [ДИП8](https://dip8.ru/shop/product/b30x6_bn13577_boss/) |
| Винт для термопласта 3 × 10, Bossard BN 13577 | 4 шт. | [ДИП8](https://dip8.ru/shop/product/b30x10_bn13577_boss/) |
