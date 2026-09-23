# yandex-sheets-ui-fix-yandex-tables

Код на CSS для исправления размера вкладок таблиц в **Яндекс таблицах**

Делает нижнюю панель с вкладками листов крупнее и удобнее для
чтения, а активную вкладку подсвечивает цветом — как в Google Sheets.

A small CSS style that improves the **Yandex Sheets** UI.
It makes the sheet tabs bar at the bottom larger and easier to
read, and highlights the active tab with color — similar to
Google Sheets.

---

## Что это? / What is it?

**RU:** Стиль меняет размеры и отступы вкладок листов внизу
редактора Яндекс Таблиц. Размеры подобраны близко к Google Sheets,
но чуть комфортнее для глаз. Активная вкладка подсвечивается
зелёным фоном.

**EN:** The style adjusts the size and spacing of sheet tabs at
the bottom of the Yandex Sheets editor. Sizes are close to
Google Sheets but slightly more comfortable. The active tab is
highlighted with a green background.

---

## Установка / Installation

**RU:** Подробная инструкция — в файле `INSTALL_RU.txt`.
**EN:** Detailed instructions — see `INSTALL_EN.txt`.

Кратко / Briefly:
1. Установите расширение **Stylus** (Chrome Web Store).
2. Откройте Яндекс Таблицу.
3. В Stylus создайте новый стиль, выберите «Применить к: ВСЕ».
4. Вставьте CSS из `styles/sheet-tabs-var4.css`.
5. Сохраните и обновите страницу.

1. Install the **Stylus** extension (Chrome Web Store).
2. Open Yandex Sheets.
3. In Stylus, create a new style, set "Applies to: ALL".
4. Paste the CSS from `styles/sheet-tabs-var4.css`.
5. Save and reload the page.

> **Важно / Important:** автор не нашёл точного URL, который
> использует Яндекс Таблицы, поэтому рекомендуется выбрать «ВСЕ».
> Это безопасно: стиль использует очень специфичные селекторы,
> которые есть только в Яндекс Таблицах.
>
> The author could not find the exact URL used by Yandex Sheets,
> so "ALL" is recommended. This is safe: the style uses very
> specific selectors that exist only in Yandex Sheets.

---

## Настройка / Customization

Все параметры меняются прямо в CSS:

| Параметр | Что делает | По умолчанию |
|----------|-----------|--------------|
| `height` | Высота вкладок | `36px` |
| `font-size` | Размер текста | `14px` |
| `padding` | Внутренний отступ | `0 1px` |
| `margin-right` | Зазор между вкладками | `4px` |
| `background-color` | Цвет активной вкладки | `#79d69361` |

---

## Структура / Structure  
yandex-sheets-ui-fix/  
├── README.md  
├── DESCRIPTION.txt  
├── INSTALL_RU.txt  
├── INSTALL_EN.txt  
├── LICENSE  
└── styles/  
    └── sheet-tabs-var4.css  


---

## Лицензия / License

MIT — см. файл `LICENSE`.
'@ | Out-File -Encoding utf8 README.md


## Авторы / Authors

**RU:**  
Ключенко М.А.  
Омск, ОмГТУ, БИТ-211  
АНО ЦО ДО «Махаон»  
(сделал данную программу, потому что масштабирование Яндекс Таблиц неполноценно)

**EN:**  
Klyuchenko M.A.  
Omsk, OmSTU, BIT-211  
ANO TSO DO "Makhaon"  
(Made this program because the scaling in Yandex Sheets is incomplete)