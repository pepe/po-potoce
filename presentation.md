---
author: Josef Pospíšil
date: 2017-04-12
title: Intro
---

# Po Potoce ~~~

===

---
author: Josef Pospíšil
date: 2017-04-12
title: Dětství
---

## Chození na potok

---

## Kameny a led

---

## Břehy

---

## Skrytá místa

===

---
author: Josef Pospíšil
date: 2017-04-12
title: Reactive Streams
---

## Reactive Streams

* Existuje více specifikací
* Asynchroní zpracování
* http://reactivex.io

---

## Rx

* Vytvoř
* Kombinuj
* Naslouchej

===

---
author: Josef Pospíšil
date: 2017-04-12
title: C#
---

## Problem

* KLs kódu
* Meziprocesová komunikace
* Tvůrce na rodičovské

---

## První přepis

* Velké kusy jen zkopírovány
* Stejná architektura
* Tvůrce onemocněl

---

## Můj přepis

* Rx.Net
* Časová smyčka pro kontroly
* Subskribce přes LINQ

---

## Výsledek

* Plně testovaná knihovna
* Aplikace jen pár řádku
* Převážně konfigurace
* Případně UI

---

## Ale hlavně ...

---

## ... jsem Reaktivní!

===

---
author: Josef Pospíšil
date: 2017-04-12
title: ClojureScript
---

# ClojureScript <3

---

## Polyconf 2014

* Zach Telman
* David Nolen
* Alexander Solovyov

---

## Stack

* Tenzing - Šablona
* Rum - React.js wrapper
* Potok - Rx.js wrapper

---

## Chromium Tools

* Tonda Hildebrandt
* cljs-devtools
* Dirac

---

## Ukaž KÓD!

```
(deftype IncStream
  ptk/UpdateEvent
  (update [_ state]
    (update state :stream/vol inc)))

(potok.core/emit! store IncStream)
```

---

## Potok

* 100 LOC
* Tři typy událostí

## Potok Rumu

* Anatomie
* Tests
* spec

---

## Živé kódování

