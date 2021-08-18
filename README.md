# Afina

****************************

Afina - Bash скрипт для установки системы Archlinux на компьютер. 
А также установки системы ArchISO, которая запущена в качестве Live CD/DVD/USB, на компьютер.

Afina - Bash script for installing the Archlinux system on a computer. 
And also, installing the ArchISO system, which is running as a Live CD/DVD/USB, on a computer.

<img src="https://raw.githubusercontent.com/maximalisimus/afina/main/image/afina.png"  height="400">

## Оглавление

1. [Информация](#Информация)
2. [Information](#Information)
4. [Использование](#Использование)
5. [Uses](#Uses)
6. [Обо Мне](#aboutrus)
7. [About](#abouten)

[:arrow_up:Информация](#Информация)

Данный скрипт предназначен для установки системы **Archlinux**, 
с помощью утилиты **dialog**.

А также, возможность установки системы **ArchISO**, который запущен в качестве Live CD/DVD/USB, на компьютер.

Скрипт можно использовать с абсолютно любым дистрибутивом *Archlunux*, кроме **bootstrap** и **arm** версии. 

Данный мастер поддерживает **UEFI** режим установки при запуске системы *ArchLinux* в режиме *UEFI*.

Данному установщику **не нужен** ни **XORG** ( **wayland** ), ни рабочее окружение ( **Desktop environment** ), ни дисплейный менеджер 
( **Display Manager** ). Данный скрипт работает полностью в консольном режиме. Достаточно только 
наличия подключения к интернету и пакета **dialog**. 

Однако, вы можете запустить скрипт и в графическом режиме, используя **Zenity**.

Также имеется возможность, установки сборки системы в виде **ArchISO - 
Live CD/DVD/USB ArchLinux** в псевдографическом режиме, используя пакет **dialog**.

Вы можете использовать данный мастер установки для самых разных режимов использования системы ArchLinux.

Например, не устанавливать графическую часть (XORG, wayland, Desktop Environment, Display Manager, драйвер видеокарты и другие). 
После этого установить пакеты для сервера и использовать систему в качестве сервера с docker и docker-container.

Или выбрать и установить только необходимые пакеты и использовать в качестве Настольного ПК.
Независимо от местоположения вашего компьютера - будь то офис или домашняя лаборатория.

[:arrow_up:Information](#Information)

This script is intended for installing the **Archlinux** system in pseudographic mode, 
using the **dialog** utility.

The script can be used with absolutely any *Archlinux* distribution, except for 
**bootstrap** and **arm** versions.

This wizard supports **UEFI** installation mode when starting the *ArchLinux* system in *UEFI* mode.

This installer **does not need** either **XORG** ( **wayland** ), nor a working environment 
( **Desktop environment** ), nor a display manager ( **Display Manager** ). 
This script works completely in console mode. Just enough availability of an 
internet connection and the **dialog** package.

However, you can also run the script in graphical mode using **Zenity**.

There is also the possibility of, installing the system assembly in the form of "ArchISO" -
Live CD/DVD/USB ArchLinux in pseudographic mode, using the dialog package.

You can use this installation wizard for a variety of modes of using the ArchLinux system.

For example, do not install the graphics part (XORG, wayland, Desktop Environment, Display Manager, video card driver, and others).
After that, install the packages for the server and use the system as a server with dokker and dokker-container.

Or choose and install only the necessary packages and use it as a Desktop PC.
Regardless of the location of your computer-whether it is an office or a home laboratory.

[:arrow_up:Использование](#Использование)

### Базовая информация

Для использования данного мастера необходимо соблюдать 2 важных условий:

1. Запуск из под суперпользователя **root**.
2. наличие настроенного подключения к интернету в вашем дистрибутиве

**Данный скрипт можно запустить из любого места**.
 
Достаточно сделать один из файлов - испольняемым и запустить его из консоли:

```
$ chmod ugo+x ./src/afina


# Для запуска в консольном режиме (dialog):

$ sudo ./src/afina -cli


# Для запуска в графическом режиме (zenity):

$ sudo ./src/afina -gui
```

Далее просто следуйсте указаниям мастер-установки.

**Желаем вам удачи**.

[:arrow_up:Uses](#Uses)

### Basic information

To use this wizard, you must comply with 2 important conditions:

1. Start from under the superuser **root**.
2. the presence of a configured Internet connection in your distribution

**This script can be run from anywhere**.

It is enough to make one of the files executable and run it from the console:

```
$ chmod ugo+x ./src/afina


# To run in console mode (dialog):

$ sudo ./src/afina -cli


# To run in graphical mode (zenity):

$ sudo ./src/afina -gui
```

Then just follow the instructions of the installation wizard.

**We wish you good luck**.

[:arrow_up:Обо Мне](#aboutrus)

Автор данной разработки **Shadow**: [maximalisimus](https://github.com/maximalisimus).

Имя автора: **maximalisimus**: [E-Mail](mailto:maximalis171091@yandex.ru).

Дата создания: **18.08.2021**

Начальная точка проекта: [aif-master](https://github.com/maximalisimus/aif-master) и [abif-master](https://github.com/maximalisimus/abif-master)

[:arrow_up:About](#abouten)

The author of this development **Shadow**: [maximalisimus](https://github.com/maximalisimus).

Author's name: **maximalisimus**: [E-Mail](mailto:maximalis171091@yandex.ru).

Date of creation: **18.08.2021**

Starting point of the project: [aif-master](https://github.com/maximalisimus/aif-master) and [abif-master](https://github.com/maximalisimus/abif-master)


