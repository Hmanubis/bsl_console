# Функция *goToFuncDefinition*
## Назначение функции
Функция позволяет перейти к определению процедуры/функции по имени в текущем тексте редактора

## Параметры функции
* [funcName] - *строка*, имя процедуры/функции

## Возвращаемое значение
Функция возвращает `true`, если в коде найдена требуемая процедура/функция и `false` в обратном случае.

## Пример вызова
```javascript
goToFuncDefinition('ЗначениеРеквизитаОбъекта');
```