# Домашнее задание к занятию "Обзор IT-систем: принципы работы современных компьютеров"

---

### Кейс 1.

Как вы думаете, какие принципиальные отличия есть между:

* компьютером секретаря

* рабочей станцией для работы с 3d графикой

* файловым сервером

* сервером, выполняющим роль маршрутизатора для выхода в интернет

Напишите ответ в свободной форме.

---

---

### Ответ 1:

- Для компьютера секретаря совсем не обязательно иметь очень крутой процессор или очень много оперативной памяти, потому что офисный компьютер предназначен лишь для офисных программ по типу Excel или Office. 
- Для рабочей станции уже стоило бы иметь хорошую оперативную память и в немалом количестве, также стоило бы иметь добротный процессор, чтобы процесс рендеринга не занимал целую вечность.
- А для серверов обязательно иметь большое хранилище данных.

---

### Кейс 2.

Чем отличаются чипсет и процессор? Напишите ответ в свободной форме.

---

### Ответ 2:

Чипсет изначально встроен в мат. плату, у процессоров такое не встречается. Чипсет заставляет работать все компоненты вместе, а процессор исполняет заданный код программ.

---

### Кейс 3.

#### Какой вариант хранилища вы бы выбрали для задач ниже (3.1-3.5)?


#### Вариант хранилища:

**А)** SSD [1], **B)** HDD [2], **C)** Ленточная библиотека [3], **D)** Собственный вариант.

#### Задачи:

* 3.1 Хранилище архива проектов, расположенное на диске с общим доступом, не критично к скорости чтения, большого объёма, должно быть доступно круглосуточно

* 3.2 Сервер баз 1С с высокими требованиями по скорости доступа к диску

* 3.3 Системный диск (на котором установлена операционная система) рабочей станции, объём небольшой

* 3.4 Хранилище ежемесячных резервных копий большого объёма, носители которого должны храниться вне офиса на случай пожара и других непредвиденных ситуаций. Подлежат использованию к крайнем случае

* 3.5 Второй диск на рабочей станции, на котором пользователь хранит данные второстепенной важности

**

[1] **SSD** (Solid-State Drive) - это твердотельный накопитель; по сравнению с HDD твердотельные накопители имеют меньший размер и вес, являются беззвучными, а также многократно более устойчивы к повреждениям (например, к падению) и имеют гораздо бóльшую скорость записи.

[2] **HDD** (Hard (magnetic) disk drive) - запоминающее устройство, основанное на принципе магнитной записи. Является основным накопителем данных в большинстве компьютеров - тот самый классический жёсткий диск (винчестер).

[3] **Ленточная библиотека** - устройства для долговременного хранения информации на ленточных накопителях. По сравнению с дисковыми массивами они не только обеспечивают предельно низкую стоимость хранения и обладают низким уровнем энергопотребления.

---

### Ответ 3:

| 3.1 | 3.2 | 3.3 | 3.4 | 3.5 |
| --- | --- | --- | --- | --- |
|  C  |  A  |  A  |  C  |  B  |

---

### Кейс 4.

Существует ли возможность использовать жёсткий диск [Western Digital WD40PURZ](https://market.yandex.ru/product--zhestkii-disk-western-digital-wd40purz/1729220435) в комплекте со старой материнской платой, в которой зашит классический BIOS?
Если да, то в каком случае. Если нет, то почему? Есть ли какой-то обходной вариант? Напишите ответ в свободной форме.

---

### Ответ 4:
Для начала, sata - контроллер должен поддерживать диски емкостью более 2.2гб, еще операционная система должна быть совместима с дисками большой емкости, вообще, чтобы поддерживать диски объемом больше 3тб на мат. плате должен быть EFI BIOS, на старых его нет. Решить эти проблемы можно несколькими способами, например, утилитами от производителя мат. платы или установить отдельный sata контроллер который поддерживает диски большоего объема.

---

### Кейс 5.

Опишите процесс загрузки компьютера с момента нажатия кнопки включения и до появления рабочего стола.
Опишите этот процесс настолько детально, насколько вы это понимаете.

---

### Ответ 5:
Начинает загружаться биос, проверяет все компоненты компьютера на их работоспособность, позже начинает подгружаться операционная система и если на ней включены программы автозапуска, то и они также начнут включаться.

---

**

## Дополнительные задания (со звездочкой*)
Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

### Кейс 6.

Попробуйте узнать IP-адрес вашего компьютера из [консоли (командной строки)](https://webkyrs.info/post/chto-takoe-komandnaia-stroka-kak-ee-zapustit-na-windows-linux-i-mac) с помощью команды `ipconfig` или `ifconfig` в зависимости от ОС, либо через графический интерфейс.
Совпадает ли он с [адресом, который видит, например, Яндекс](https://internet.yandex.ru)? Как вы думаете, почему?

---

### Ответ 6:

Не совпадает, наверное, потому что у браузера другое подключение (?)

---

### Кейс 7.

Какой процессор вы выберете - Intel Core i5 9600K или Intel Core i7 7700K?
Почему Intel Core i5 9600K или Intel Core i7 7700K? [Изменится ли мнение после просмотра этого сравнения?](https://cpu.userbenchmark.com/Compare/Intel-Core-i5-9600K-vs-Intel-Core-i7-7700K/4031vs3647) Опишите ход ваших мыслей.
Какую материнскую плату вы выберете для выбранного процессора?

---
### Ответ 7:

i5 9600k потому что это последнее поколение значит оно мощнее. 
ASUS PRIME B360M-K.
