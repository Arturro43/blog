---
layout: post
title: Ten o zabezpieczaniu telefonu z Androidem
tags: android prywatność bezpieczeństwo
published: false
---

Android to obecnie najpopularniejszy system na świecie. Używa go obecnie [36,5% wszystkich urządzeń na świecie.](http://gs.statcounter.com/os-market-share#monthly-201902-201903-bar). Jest to również prawdopodobnie najgorzej zabezpieczony system, który jest tak szeroko używany. Jak go więc zabezpieczyć?

<h2>Ten artykuł powstał na prośbę jednego z moich czytelników (pozdrawiam, Janku!). Jeżeli chcesz, abym poruszył jakiś temat na łamach mojego bloga - [napisz do mnie!](https://arturro43.github.io/about/)</h2>

Wróćmy jednak do tematu artykułu - zabezpieczanie (bardziej technicznie: hardening) telefonu z systemem Android.  
Jak wiadomo nie od dziś Android posiada naprawdę spore kłopoty z bezpieczeństwem (mimo tego, że jakby nie patrzeć to Linux ;). Przykłady:  
[Miliony urządzeń z Androidem jest podatnych tuż po wyjęciu z pudełka](https://www.wired.com/story/android-smartphones-vulnerable-out-of-the-box/)  
[Android i problemy z łatkami bezpieczeństwa](https://www.theverge.com/2018/4/13/17233122/android-software-patch-trust-problem)  
[Instalator Fortnite może zainstalować nam złośliwą aplikację](https://www.cnet.com/news/fortnites-battle-royale-with-android-security-problems-is-just-getting-started/)  
[95% telefonów z Androidem można zhakować MMSem](https://zaufanatrzeciastrona.pl/post/95-telefonow-z-androidem-mozna-zhakowac-mmsem-i-trudno-sie-przed-tym-zabezpieczyc/)  
[Fałszywe aplikacje bankowe w oficjalnym sklepie Google](https://zaufanatrzeciastrona.pl/post/uwaga-na-nieustajace-ataki-na-klientow-bz-wbk-w-sklepie-google-play/)  

Czytelnik, który do mnie napisał martwi się bezpieczeństwem swojego telefonu, gdyż jest on jego głównym narzędziem do zarządzania firmą, a także całym życiem. Zakładam, że takich osób jest znacznie więcej - w końcu smartfony dla pewnej części społeczeństwa zastąpiły komputery i zapewne każdy kto martwi się o swoją firmę, oszczędności czy swoje życie prywatne chciałby się dowiedzieć czegoś o zabezpieczaniu swojego telefonu. Co ciekawe - próżno jest szukać poradników, które są pisane przez osoby znające system Android ponadprzeciętnie, które są zorientowane w świecie cyberbezpieczeństwa i które chcą wygody łącząc ją z bezpieczeństwem urządzenia. Można więc potraktować mój poradnik jako jeden z nielicznych. Ale wracając...

<h3>Zaniedbywanie bezpieczeństwa telefonu można porównać do zostawiania otwartych drzwi w domu</h3>

I nie, to nie jest przesada. Na naszych telefonach posiadamy aplikacje bankowe, prywatne rozmowy, prywatne zdjęcia, prywatne konta. Dla wielu osób telefony komórkowe stały się głównymi narzędziami zarządzania całym życiem i jedynym narzędziem dostępu do informacji, kultury, wiedzy czy społeczności (czyt. internetu). Uważam więc, że porównanie zostawienia telefonu w miejscu publicznym, które nie jest zabezpieczone przed dostępem innych osób do pozostawienia kluczy do domu z przyklejoną karteczką z naszym adresem, a brak zabezpieczenia telefonu przed (uwaga, obrazowość) niepowołanym dostępem z internetu do podania komuś hasła do konta bankowego nie jest wyolbrzymieniem, lecz pokazaniem problemu jakim jest brak zabezpieczenia narzędzi dostępowych do naszego prywatnego życia. Koniec wstępu, przejdźmy do sposobów, które ja używam, by spać spokojnie

<h4>To co nie wymaga wielkiego wysiłku</h4>

1. Blokada ekranu - jest absolutną podstawą. Bez niej każdy kto będzie mieć fizyczny dostęp do naszego telefonu będzie w stanie zrobić z naszym telefonem absolutnie wszystko. [Zrezygnujmy jednak z odblokowywania twarzą](https://www.youtube.com/watch?v=BGgQ9woZQOg), a także [wzorem](https://niebezpiecznik.pl/symantec/czysc-ekran-swojego-telefonu/), bo [łatwo je odgadnąć](https://www.wired.com/story/android-unlock-pattern-or-pin/). Większość producentów pozwala nam na użycie ponad 4 znakowego pinu (6 znaków to według mnie minimum) a także hasła (co jest obecnie najbezpieczniejszym rozwiązaniem)
2. [Find my phone](https://www.google.com/android/find) - w przypadku gdy zauważymy, że zgubiliśmy powinniśmy zaregować blokując telefon i wymazując dane
3. 
