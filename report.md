# Отчёт о тестировании приложения "Precision"

## Краткое описание

05.03.2021 Создано базовое приложение ["Precision"](src/Main.java) на основе [кода (см. задание 2)](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)


### Описание тестов

Проведены следующие виды тестирования:  функциональное тестирование

В качестве тестовых данных использовались следующие значения    

Постоянный бонус  
`double regularBonus = 0.3;`  

Дополнительный бонус  
`double specialBonus = 0.6;`  

Результирующий бонус должен быть суммой указанных выше бонусов  
`double totalBonus = regularBonus + specialBonus;`

## Результаты
Тест провален: [Значение totalBonus вычисляется не корректно](https://github.com/DoroshenkoDenis/JavaHomeWork2_2/issues/1)

## Общие рекомендации
Ввести округление расчётов до двух знаков после запятой, заменив  
`System.out.println(totalBonus);`  
на   
`System.out.printf("%.2f",totalBonus);`
