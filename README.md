## Описание проекта

![skin_preview](https://raw.githubusercontent.com/Mahamadovich/TQW/master/Installation/main.png)

Обложка для рабочего стола показывающая время молитвы, имена Всевышнего с переводом (в удобном для запоминания формате) и содержащая сборник "Сахих аль-Бухари". Ну и стильный виджет с часами, позволяющий вам видеть(анализировать) загруженность своего компьютера.

### Как пользоваться

Для работы обложки вам понадобится:
1. [Rainmeter](https://www.rainmeter.net/) - программа, позволяющая применять обложки для рабочего стола.
2. [Последняя версия нашей обложки](https://github.com/Mahamadovich/TQW/releases)

### Время молитв

**Rainmeter** не предлагает простого способа определения местоположения, поэтому его придётся ввести вручную:

```praytimes.ini
...
[Variables]
lat=45.000    // Широта - достаём из гугл/яндекс карты
lon=45.000    // Долгота - достаём из гугл/яндекс карты
gmt=180       // Часовой пояс (180 это +3 часа по МСК, т.е. +1 час = 60. Пример: +5 часов = 300; -5 часов = -300)
method=3      // Метод расчёта времени молитв:
// University of Islamic Sciences, Karachi: 1
// ISNA: 2
// Muslim World League: 3
// Umm Al Qura: 4
// Egyptian Authority of Survey: 5
// Мне ни один с точностью не подошел, лишь приблизительно. 
// В планах - возможность ручной корректировки.
...
```

### Обновления

Уведомления об обновлениях в самой обложке не осуществлены (пока), поэтому, чтобы не пропустить важное обновление, подпишись на [канал в телеге!](https://t.me/taqwia) Новости об обновлениях и ничего лишнего.

### Поддержка

Обсудить проект, предложить улучшение, либо свою помощь - [здесь](https://t.me/taqwia_chat).
