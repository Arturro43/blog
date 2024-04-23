---
layout: post
title: Ten o minimalizacji zbieranych danych
tags: prywatność
date: 2019-02-02T00:00:00+02:00
published: true
---

O tym dlaczego minimalizacja ilości pobieranych danych od klientów jest ważna możnaby napisać książkę.

Problem jest taki, że nie każdy wie w czym jest problem.
Dzisiaj, rozpoczynając swojego bloga, chcę pokazać

<h2>Dlaczego ilość zbieranych danych jest wprost proporcjonalna do głupoty administratorów.</h2>


Zastanówmy się na początku co jest wystarczające do odebrania towaru zakupionego przez internet w punkcie odbioru osobistego.
Odpowiedź: *imię, nazwisko, numer zamówienia.*

Teraz zastanówmy się co jest wymagane przez większość sklepów internetowych do odbioru stacjonarnego.
Odpowiedź: *imię, nazwisko, adres, numer telefonu, adres e-mail, numer zamówienia.* **I to przy zwykłym rachunku.** Czy sami nie uważacie, że jest to trochę za dużo?


Żeby zobrazować ile te dane są tak naprawdę warte (nie chodzi mi tu o wartość pieniężną) i to jak bardzo niebezpieczne jest lekceważenie, najczęściej przez osoby nietechniczne, problemu nadmiernego zbierania danych  przedstawię sposób (nie do końca dobrego) wykorzystania tych danych.

**Adres email** - spamming

**Numer telefonu** - spamming

<h3>…tak ta lista wyglądałaby ponad 4 lata temu.</h3>


Tak jest teraz:

**Adres email** - spamming, phishing, w połączeniu z imieniem - skuteczny phishing, w połączeniu z hasłem do poczty z wycieków z serwisów internetowych - [jeszcze skuteczniejszy phishing](https://zaufanatrzeciastrona.pl/post/nowa-metoda-szantazu-przestepcow-z-prawdziwym-haslem-uzytkownika/), a także możliwość uzyskania dostępu do wszystkich kont używających tego maila, a co za tym idzie - [możliwość wyłudzeń na znajomych ofiary za pośrednictwem np. Facebooka](https://niebezpiecznik.pl/post/ojciec-oszukal-mnie-przez-facebooka-czyli-dwa-ataki-swietnie-przygotowanego-zlodzieja-z-kryptowalutami-w-tle/), [dodatkowe źródło](https://niebezpiecznik.pl/post/jak-wyludzic-od-znajomego-800-zlotych-przez-facebooka/) i jeżeli jest się kimś "ważniejszym" - możliwość przeprowadzenia ataku SIM Swap, o którym napisałem niżej

**Numer telefonu** - spamming telefoniczny, niebywale skuteczne (zwłaszcza na osobach mniej "w temacie" i osobach starszych) ataki socjotechniczne (patrz: oszustwo "na wnuczka" "na policjanta", oferty kupna np. garnków, oferty usług itp.), w połączeniu z imieniem i nazwiskiem - zwiększenie skuteczności wyżej wymienionych ataków socjotechnicznych, ataki socjotechniczne polegające na wydobywaniu większej ilości informacji (np. podawanie się za pracownika banku i proszenie o części numeru PESEL, czy nazwiska panieńskiego matki), jeżeli jest się kimś "ważniejszym" w połączeniu otrzymanie dostępu do (przepraszam że to powiem) bardziej wartościowej skrzynki mailowej, a dodatkowo [możliwość wyprowadzenia środków z portfela kryptowalut](https://motherboard.vice.com/en_us/article/a3q7mz/hacker-allegedly-stole-millions-bitcoin-sim-swapping)




<h4>Nieźle co? A to dopiero początek…</h4>




Zastanów się teraz ile razy podałeś swoją prawdziwą datę urodzenia, swój prawdziwy adres zamieszkania, swój numer telefonu w miejscu, które wcale nie potrzebuje takich informacji (fora, konta na witrynach usługowych itp.). Wszystkie te dane mogą ujrzeć światło dzienne w każdej chwili przez niedbałość administratorów Twoich danych (czytaj: administratorów miejsca, w którym te dane pozostawiłeś). W tym momencie można stwierdzić, że to administratorzy są w pełni odpowiedzialni za wszystkie dane jakie zbierają. Otóż nie… Przynajmniej nie do końca…

**Wycieki zdarzają się, zdarzały się i zdarzać się będą**

Każdy człowiek uczy się na błędach. Każdy. Dlaczego więc administratorzy nie uczą się na błędach innych? Nauka wyniesiona z tych wszystkich wycieków powinna być taka - częste audyty infrastruktury, częste aktualizacje, lepsze funkcje haszowania haseł, szyfrowanie danych osobowych (w tym maila, czy pozostałych danych), minimalizacja zbieranych danych. Co tymczasem robią administratorzy? Wyciekająca baza z pewnego polskiego sklepu internetowego z hasłami zahaszowanymi md5cryptem zamiast bcryptem, do odbioru stacjonarnego dalej potrzeba podać swój adres zamieszkania.

Poniżej porównanie odporności (mocy) funkcji skrótu na podstawie ilości sprawdzeń haszy na sekundę (porównanie md5crypt i bcrypt)

[<img src="../../images//hashcat md5crypt vs bcrypt.jpg" alt="Klinij mnie, a zabiorę cię do strony odzyskiwacza haseł" style="width: 720px;"/>](https://hashcat.net/hashcat/)



<h5>Jak żyć panie premierze, jak żyć?</h5>

Godnie. Starajmy się minimalizować naszą ekspozycję na wycieki. Podajmy fałszywe dane - podstawą jest fałszywa data urodzin np. 1 stycznia, bonus za 1970 ;), podajmy fałszywe adresy zamieszkania; używajmy wielu maili na różnych serwisach (gmail (i inne poczty zapewne też) posiada opcję autoforwardowania na dany adres, więc warto się przyjrzeć tej opcji), nie podajmy czegoś co wydaje nam się niepotrzebne. W skrócie - podawajmy wymagane minimum, jeżeli nawet to minimum włącza u nas w głowie lampkę - podajmy fałszywe dane.
Jeżeli chcemy się sprzeciwiać nadmiernemu data gatheringu - wspierajmy takie organizacje jak [Panoptykon](https://panoptykon.org/). Wysyłajmy do administratorów zapytania w oparciu o [art. 5 ust. 1 pkt c RODO](https://gdpr.pl/artykul-5-zasady-dotyczace-przetwarzania-danych-osobowych) czy naprawdę potrzebują tych wszystkich danych jakie zbierają.

Stay safe.
