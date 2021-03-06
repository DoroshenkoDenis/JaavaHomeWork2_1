# Отчёт о тестировании приложения "Precision"

## Краткое описание

05.03.2021 Создано базовое приложение ["Precision"](src/Main.java) на основе [кода (см. задание 2)](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)


### Описание тестов

Проведены следующие виды тестирования:  функциональное тестирование

## Результаты
Тест провален: [Некорректный расчёт итогового бонуса клиента.](https://github.com/DoroshenkoDenis/JavaHomeWork2_2/issues/1)

## Общие рекомендации
Доработать код
Ввести округление расчётов до двух знаков после запятой, заменив  
`System.out.println(totalBonus);`  
на   
`System.out.printf("%.2f",totalBonus);`
