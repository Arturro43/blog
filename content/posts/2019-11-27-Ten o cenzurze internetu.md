---
layout: post
title: Wciskają przycisk i... nie ma internetu.
tags: bezpieczeństwo wolność
published: false
---

16 listopada o godzinie 13:33 rząd Iranu przez protesty związane ze wzrostem cen ropy postanowił wyłączyć internet, by ukryć przed światem łamanie praw człowieka np. strzelając do protestujących ostrą amunicją i zabijając przy tym co najmniej 106 osób.

Co jeżeli w pewnym momencie rząd Polski postanowi również wyłączyć internet i nie będziemy mieli kontaktu ze światem, a może nawet z najbliższymi? A co jeżeli wyjedziesz do jakiegoś kraju na wakacje i to on postanowi wyłączyć Internet? Przed wami prawdopodobnie pierwszy pisany po polsku poradnik, który pomoże wam pozostać połączonym ze światem w przypadku Internet blackoutu w państwie, w którym przebywasz. Zapraszam.



Część pierwsza - rozpoznanie.

Istnieją różne sposoby na to, by "wyłączyć internet" w danym państwie. Jednym z nich, które nawet teraz stosuje polski rząd to blokowanie na poziomie DNS. Jak działa DNS? Domain Name System jest niczym książka telefoniczna - wyszukujesz nazwę i wybierasz numer. DNS bierze to co zostało wpisane w pasku adresu przeglądarki (np. arturro43.github.io) i przypisuje do tego adres IP (np. 185.199.109.153). No i tyle. Dzięki temu Twój komputer jest w stanie połączyć się do przykładowo mojej strony, albo do Facebooka czy Twittera. W momencie gdy zablokujemy możliwość "rozwiązania" (ang. resolve) zapytania do serwera DNS blokujemy w ten sposób możliwość połączenia się ze stroną. Uzyskujemy wtedy ten znany błąd "Ta witryna jest nieosiągalna".