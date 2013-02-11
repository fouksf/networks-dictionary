# Речник на термините от компютърните мрежи и комуникациите

Липсата на учебници и научна литература на български език в сферата на
компютърните мрежи и комункациите поражда условия за неправилно използване на
чуждоезични термини. Целта на този речник е да послужи за справочник на
обучаващите се в тази сфера и да помогне за популяризирането на употребата на
българските преводи на термините.

## Как да допринеса към речника?

За да допринесете към речника, трябва да сте съглани работата Ви да бъде
разпространявана под лиценза
[CC BY-SA 2.5 BG](http://creativecommons.org/licenses/by-sa/2.5/bg/)

### Примерни записи

Общ случай:

```yaml
term:
  превод: тѐрмин
  мн.ч: тѐрмини, (два) тѐрмина
  род: мъжки
  значение: Дума, специализирана да назовава точно определено понятие в някоя
            научна област.
  пример: Географски термини.
  справка: Koral EuroDict
```

Никое от изредените под `term` полета няма задължителен характер. Дори само
добавяне на термин на английски език без нито едно от тях, се смята за ценен
принос към пълнотата на речника.

Пример:
```yaml
broadcast:
```

Полето `препратка` се използва за насочване към допълнителна информация относно
термина.

Пример:
```yaml
network layer:
  превод: мрѐжов сло̀й
  мн.ч: мрежовѝ сло̀еве, (два) мрежовѝ сло̀я
  род: мъжки
  значение: Слой 3 от референтния OSI модел.
  препратка: OSI reference model
```

Съкращенията в речника препращат към несъкратения термин на английски език.

Пример:
```yaml
CSMA/CD:
  препратка: carrier sense multiple access with collision detection
```

### Уда̀рени букви

Под Линукс можете да добавите ударение върху буква като поставите маркера
непосредствено след нея и изпълните клавишната комбинация `Ctrl Shift
u0300`. Под уиндоус клавишната комбинация е `Alt +300` (забележете плюса).

В редактора Емакс ударение се добавя като поставите маркера непосредствено след
ударената буква и изпълните комбинацията `C-x ucs-insert <RET> 0300 <RET>`.

За удобство: А̀а̀, Ъ̀ъ̀, О̀о̀, У̀у̀, Ѐѐ, Ѝѝ
