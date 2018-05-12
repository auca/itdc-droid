# ITDC-DROID
Практическая работа №1
======================

## Организация работ

Рекомендуется выделить отдельную директорию для всех практических работ и задач.

![Example](http://i.imgur.com/0nh3Ttq.png)

## Задание №1: Среда разработки

Подготовьте [среду разработки](https://github.com/auca/itdc-droid/blob/master/Environment.md)
на Вашей машине.

## Задание №2: Создание проекта

Создайте новый проект Android приложения по шаблону "Blank Activity".
Познакомьтесь со структурой проекта.

## Задание №3: Запуск приложения

Создайте и запустите новое виртуальное устройство Android (AVD). Перешлите и
запустите ваше приложение на этом устройстве.

Используйте Android образы `x86` или `x86-64` и драйвер виртуализации QEMU
эмулятора Intel Hardware Accelerated Execution Manager (HAXM). В противном
случае, эмулятор будет работать медленно, так-как ему нужно будет
интерпретировать ARM команды на процессоре x86.

Передайте и запустите приложение на Вашем Android устройстве. На операционной
системе Windows убедитесь, что у Вас установлен [отладочный драйвер](http://developer.android.com/tools/extras/oem-usb.html).
Вам также необходимо включить режим [USB отладки](http://developer.android.com/tools/device.html)
на устройстве.

## Задание №4: Отладка приложения

Откройте Java код главной Операции (Activity). Установите точку останова на
методе `onCreate`. Запустите приложение в эмуляторе или на Вашем устройстве.
Попробуйте выполнить несколько инструкций Java шаг за шагом в среде разработки.

## Чтение

[Android Development Tools](https://developer.android.com/guide/)
