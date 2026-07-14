# Bruce Encoder Fix for LilyGO T-Embed CC1101

[RU]

Модифицированная версия Bruce Firmware v1.15 для LilyGO T-Embed CC1101.
#LilyGO #T-Embed #CC1101 #fix #encoder
Данная модификация предназначена **только для LilyGO T-Embed CC1101**.

Не рекомендуется использовать эту прошивку на других устройствах, так как изменения сделаны специально под аппаратную конфигурацию T-Embed CC1101 и его систему ввода.

Этот форк исправляет проблему с аппаратным энкодером (колёсиком), когда он:
- перестаёт работать;
- пропускает шаги;
- хаотично переключает пункты меню;
- работает нестабильно или полностью выходит из строя.

Теперь устройство можно полноценно использовать даже без исправного энкодера. Никакая перепайка или замена компонентов не требуется.

## Управление после изменения

Энкодер заменён логикой управления через кнопки:

- **Короткое нажатие центральной кнопки энкодера** — обычный выбор пункта меню (Select).
- **Удержание центральной кнопки энкодера** — имитация прокрутки вперёд (Next / Scroll Down).
- **Короткое нажатие боковой кнопки** — возврат назад (Back / Escape).
- **Удержание боковой кнопки** — имитация прокрутки назад (Previous / Scroll Up).

Таким образом, основные функции энкодера сохраняются даже при его неисправности.
## Bug Reports / Сообщения об ошибках

Если вы нашли баг, проблему или нестабильную работу прошивки, сообщите об этом:

Telegram: **@offerskoy**

Опишите:
- что именно произошло;
- как повторить проблему (если возможно).

Спасибо за помощь в улучшении прошивки.
---

[EN]

Modified version of Bruce Firmware v1.15 for LilyGO T-Embed CC1101.

This fork fixes issues with the hardware rotary encoder, including:
- encoder failure;
- missed steps;
- random menu scrolling;
- unstable or completely broken encoder behavior.

No hardware repair or soldering is required.

## New Controls

The encoder functions are emulated through physical buttons:

- **Short press center encoder button** — normal menu selection (Select).
- **Hold center encoder button** — scroll forward (Next / Scroll Down).
- **Short press side button** — back action (Back / Escape).
- **Hold side button** — scroll backward (Previous / Scroll Up).

---

## Disclaimer

This project is based on the original Bruce Firmware project.

Original project:
https://github.com/pr3y/Bruce

All credits for the original firmware belong to the Bruce developers.

This repository contains only modifications made to improve usability of LilyGO T-Embed CC1101 devices with faulty rotary encoders.

---

## Bug Reports

If you find any bugs, problems or unexpected behavior in this modification, please contact me:

Telegram: **@offerskoy**

Please describe:
- your device model;
- firmware version;
- what happened;
- how to reproduce the problem.

---

## Developer

Modification by:
**@offerskoy**

Distributed freely as open-source software.
