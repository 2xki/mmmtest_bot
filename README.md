# MMMTest Bot

Ein bot für die  [mmmtest](https://www.mmmtest.at) Fahrschul lern Software.
Er kann alle frage von B Grund und Spezialwissen. 
Mann kann aber mit der bot_lerning.js dem bot auch noch andere Fragen beibringen.

---

## Setup

* Logge dich in deinen MMM-test Account ein und gehe zu dem Fach das du lernen willst.
* Öffne die Console in deinem Browser und füge mit copy/past den code von bot.js ein.
* enjoy ;)

![alt text](images/fach.png)

![alt text](images/console.png)

![alt text](images/insert_code.png)

Du musst für jedes fach den Code neu einfügen.

## Lerning

Wenn du dem bot neue Fragen beibringen willst, musst du die JSON data updaten. bot_learning.js wird die fragen durchgehen und wenn es eine Falsch beantwortet diese zu jsonData hinzufügen. Am Ende musst du die jsonData exportieren und in den Code einfürgen.

Json exportieren:

```javascript 
    JSON.stringify(jsonData);
```

# LICENCE

mmmtest_bot is released under "THE BEER-WARE LICENSE", see `LICENSE` for details.