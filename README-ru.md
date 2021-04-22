# Dynamic Parent

[English](README.md) | __Русский__

__Dynamic Parent__ - это аддон для Blender.

Он позволяет быстро включать/выключать связь родитель-потомок между объектами. Делается это через анимированный констреинт `Child Of`. При выключении сохраняется положение потомка относительно родителя.

## Требования

Аддон требует Blender 2.83 и новее.


## Установка

- [Скачайте последнюю версию](https://github.com/romanvolodin/dynamic_parent/releases/latest) аддона. Распаковывать архив не нужно.
- Запустите Blender, перейдите в меню `Edit` → `Preferences...`
- В столбце слева нажмите кнопку `Add-ons`. Затем вверху нажмите кнопку `Install...`
- В открывшемся окне выделите скачанный архив.
- Включите галку, чтобы активировать аддон.


## Использование
Выделите несколько объектов, родительский объект должен быть выделен последним. 

Нажмите `Create` чтобы создать констреинты и анимационный ключи. Перейдите в другой кадр. Нажмите `Disable` чтобы выключить констреинты для выделенных объектов.

Меню `Clear` позволит запечь анимацию и/или удалить все созданные констреинты.