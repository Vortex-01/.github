# Проект Вихрь-01

## Цель
Создайте недорогой спутник под названием Vortex-01, который обеспечит бесплатную сеть Wi-Fi через спутниковое соединение. Спутник будет оснащен датчиками, системами питания и удаленной системой безопасности.

## Технические характеристики спутника

- **Имя:** Вихрь-01
- **Функция:** Предоставление бесплатного Интернета через спутник.

### Основные компоненты

- **Raspberry Pi 4B:** Центральный компьютер для обработки данных и управления.

### Датчики

- **Датчик атмосферного давления:** **BMP180** - Доступный датчик для измерения давления и высоты.
- **Датчик ускорения (IMU):** **MPU-6050** — Сочетает в себе акселерометр и гироскоп, идеально подходит для контроля движения и ориентации.
- **Датчик радиации:** **RADFET** — Опционально, для экономичного мониторинга радиационного воздействия.

### Антенны

- **Широкополосная дипольная антенна:** Самодельная дипольная антенна для недорогой радиосвязи.
- **Антенна Яги:** антенна Яги, сделанная своими руками, для улучшения направления и усиления связи, изготовленная из доступных материалов.

### Энергетические системы

- **Солнечные панели**: **Поликристаллические панели** - Экономичны и достаточны для выработки энергии в небольших космических проектах.
- **Контроллер солнечной зарядки:** **ШИМ-контроллер** - Доступное решение для базового управления зарядкой солнечных панелей.
- **Аккумулятор:** Автомобильные аккумуляторы или **восстановленные аккумуляторы 18650**. - Дешевая альтернатива хранению энергии с использованием повторно использованных аккумуляторов от старых ноутбуков.

### Термоконтроль

- **Теплоодеяла:** **Майларовые одеяла** - Дешевое решение для теплоизоляции с использованием легких и светоотражающих материалов.

### Двигательная установка

- **Подруливающие устройства на холодном газе.** Подруливающие устройства, сделанные своими руками, с использованием пейнтбольных баллонов с CO2 и выпускными клапанами для безопасных и экономичных маневров.

### Системы навигации и управления

- **GPS:** **GPS-модуль NEO-6M** - Доступный GPS-модуль, подходящий для базовой навигации и отслеживания местоположения.

## Система безопасности

- **Функция:** отключите топливную систему и активируйте гигантский парашют в случае неисправности или опасности.
- **Механизм:** активируется удаленно для обеспечения безопасности в случае критического сбоя.

##Программное обеспечение

- **Разработка:** Использование Ubuntu, Python, C, ассемблера и Java.
- **Связь:** посредством радиочастотных сигналов.

### Функции

- Код для управления датчиками
- Код для связи и передачи данных
- Код для системы безопасности

## Проектирование спутников

- **Структура:**
 - **Формат:** Компактный и легкий, изготовлен из стали и алюминия.
 - **Солнечные панели:** для производства энергии.
 - **Аккумулятор:** Автомобильный аккумулятор или аккумуляторы 18650 для хранения энергии.

## Запуск

- **Подготовка:** Сборка на стартовой площадке.
- **Топливо:** Бензин будет добавлен на стартовой площадке.
- **Процедуры безопасности:** Безопасное расстояние и удаленная активация системы безопасности.

### Планирование запуска

- **Этап сборки:** соберите спутник и залейте топливо на стартовой площадке.
- **Дистанционная активация:** Дистанционно активируемая система безопасности для отключения топлива и раскрытия парашюта в случае чрезвычайной ситуации.

## Репозитории

- **3D-модель:** [GitHub — Модель Vortex-01](https://github.com/Vortex-01/Model)
- **Исходный код:** [GitHub - Исходный код Vortex-01](https://github.com/Vortex-01/Source-Code)

## Цель признания

- **Цель:** использовать проект Vortex-01 в качестве демонстрации технических и инновационных навыков, стремясь привлечь внимание таких учреждений, как Массачусетский технологический институт.
