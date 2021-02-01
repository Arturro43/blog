---
layout: post
title: Ten o tym jak znalazłem 61 tysięcy polskich adresów email
permalink: '/wyciek-audiostereo'
tags: wyciek dorked
published: true
---

W wolnym czasie bawię się [Google Dorks](https://niebezpiecznik.pl/post/sterowanie-projektorami-muzeum-ciekawe-rzeczy-znajdziesz-w-google/). Tym razem udało mi się znaleźć coś bardzo ciekawego czego się raczej nie spodziewałem.

**20 stycznia** bawiłem się w szukanie wycieków na bazie jednego paste'a na pastebinie znalezionego przez [@leak_scavenger](https://twitter.com/leak_scavenger) (taki fajny Twitterowy bot szukający wycieków publikowanych na pastebinie). Znalazłem tam jakiś polski adres, więc wkleiłem go do Google.

Jestem bardzo zdeterminowany, więc dotarłem aż do trzeciej strony wyników, a tam moim oczom ukazał się wynik taki jak na załączonym obrazku:

<img src="{{ site.baseurl }}/images/as-1.png" alt="1" style="width: 500px;"/>

W jakim ja byłem szoku jak zobaczyłem ścieżkę do pliku w adresie url XD

[https://www.audiostereo.pl/mailing/listMails.txt](https://www.audiostereo.pl/mailing/listMails.txt)

No to co, usuwamy nazwę pliku i patrzymy do folderu?

<img src="{{ site.baseurl }}/images/as-2.png" alt="2" style="width: 720px;"/>

Ups. Na tym miejscu pragnę zaznaczyć obecność pliku send.log, w którym prawdopodobnie są maile nawet tych osób, które usunęły się z listy mailingowej.
[https://www.audiostereo.pl/mailing/send.log](https://www.audiostereo.pl/mailing/send.log)

61063 linijki.

<img src="{{ site.baseurl }}/images/as-3.png" alt="3" style="width: 500px;"/>

61063 adresów email dostępnych publicznie i zindeksowancyh przez Google.

<h2>Sprawę zgłosiłem administratorom, a oni nie raczyli się zareagować przez około 3 tygodnie</h2>

Jak zawsze przy takich sprawach - powiadamiam administratorów, staram się o jak najwięcej uwagi, lecz no jak widać bez skutku ;)

O wycieku powiadomiłem również Troya Hunta (ten od [have i been pwned?](https://haveibeenpwned.com/)) i zapewne wkrótce baza pojawi się w jego serwisie.


Tymczasem chcę podziękować administratorom za prężną współprace i szybką reakcję (z publikacją czekałem aż do momentu kiedy uzyskam 403). Dzięki wam z pewnością nikt nie został zaspamowany przez boty szukające takich otwartych baz w indeksie Google ;)

<img src="{{ site.baseurl }}/images/as-4.png" alt="4" style="width: 500px;"/>

Jaka szkoda, że mail na którym się zarejestrowałem tylko i wyłącznie na audiostereo jest teraz zaspamowywany XD
