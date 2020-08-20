# Отчёт о тестировании Money Transfer
## Краткое описание
20.08.2020 было проведено было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
- [Выход за границы типа int при сложении](https://github.com/Rusdos/Netology-Java2.1/issues/1#issue-682661826)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

- ### 
- ###   
#### Предусловия 
Установить IntelliJ IDEA согласно 
[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

#### Шаги
1. запустить IntelliJ IDEA
1. в IntelliJ IDEA открыть папку с проектом
1. в папке src открыть класс Main
1. нажать Ctrl+Shift+F10

В качестве тестовых данных использовались данные :

- текущий баланс карты = 2_000_000_000; сумма пополнения =500_000_000;

Тестирование производилось в следующем окружении:

- ОС Windows 10 x64
- IntelliJ IDEA 2020.2 (Community edition) Runtume version 11.0.7+10-b944.20 amd64
