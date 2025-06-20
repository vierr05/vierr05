# Примеры всех основных элементов Markdown

## 1. Заголовки
```markdown
# Заголовок 1 уровня
## Заголовок 2 уровня
### Заголовок 3 уровня
#### Заголовок 4 уровня
##### Заголовок 5 уровня
###### Заголовок 6 уровня
```

## 2. Форматирование текста
```markdown
*Курсив* или _Курсив_  
**Жирный** или __Жирный__  
***Жирный курсив***  
~~Зачёркнутый текст~~  
`Встроенный код`  
```

## 3. Списки
### Нумерованный список
```markdown
1. Первый пункт
2. Второй пункт
3. Третий пункт
```

### Маркированный список
```markdown
- Пункт 1
- Пункт 2
  - Вложенный пункт
  - Ещё вложенный
- Пункт 3
```

### Список задач
```markdown
- [x] Сделать домашку
- [ ] Купить продукты
- [ ] Позвонить маме
```

## 4. Ссылки и изображения
```markdown
[Текст ссылки](https://example.com)
![Альтернативный текст](путь/к/изображению.jpg)
```

## 5. Таблицы
```markdown
| Заголовок 1 | Заголовок 2 | Заголовок 3 |
|-------------|-------------|-------------|
| Ячейка 1    | Ячейка 2    | Ячейка 3    |
| Ячейка 4    | Ячейка 5    | Ячейка 6    |
```

## 6. Цитаты
```markdown
> Это цитата первого уровня
>> Вложенная цитата
> Возврат к первому уровню
```

## 7. Блоки кода
### Однострочный код
`` `git status` ``

### Многострочный блок кода
````markdown
```python
def hello():
    print("Hello World!")
```
````

## 8. Горизонтальные линии
```markdown
---
***
___
```

## 9. Встроенный HTML (если нужно)
```markdown
<details>
<summary>Спойлер</summary>
Скрытый текст под спойлером
</details>
```

## 10. Специальные символы (экранирование)
```markdown
\* Экранированный символ звёздочки \*
```

## 11. Сноски
```markdown
Вот текст со сноской[^1].

[^1]: А вот и сама сноска.
```

## 12. Emoji
```markdown
:smile: :heart: :rocket:
```

## 13. Внутренние ссылки (якоря)
```markdown
[Перейти к заголовкам](#1-заголовки)
```

## 14. Комментарии (не отображаются в рендеринге)
```markdown
<!-- Это комментарий, его не видно в результате -->
```
