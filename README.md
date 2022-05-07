---
title: "Analiza Skupien"
author: "Wiktoria Paluch"
output: html_document
---

## Opis

<p> Praca skupia się na analizie zbioru danych - piwo.csv, w którym zebrano informacje odnośnie 20 popularnych marek piw. Celem projektu jest pogrupowanie marek pod względem podobieństwa analizowanych cech. Badania odpowiedzą na pytanie, które piwa można uznać za najbardziej nietypowe, a które można zaklasyfikować jako przeciętne.</p>

## Opis zbioru danych

Zbiór danych zawiera następujące zmienne: <ul>
    <li> zawartość alkoholu - procentowa zawartość alkoholu w butelce piwa [%], 
    <li> cena - cena jednostkowa za butelkę piwa [zł],
    <li> dostępność - dostępność w wybranych krakowskich sklepach spożywczych[pkt], 
    <li> znajomość - rozpoznawalność marki wśród ankietowanych[pkt], 
    <li> preferencje - preferencje ankietowanych do danej marki piwa[pkt].
</ul>

# Wnioski z badań

Wszystkie metody podziału obiektów wskazały podobne wyniki, widać zależności ze jeżeli dane piwo np. Żywiec i Kasztelan charakteryzują się dużym współczynnikiem preferencji to zawsze znajdowały się razem w danej grupie. Na różnice pomiędzy danymi pogrupowaniami istotny wpływ ma nie tylko metoda grupowań ale również i sposób standaryzacji zmiennych oraz sposób obliczania miary odległości.

### Bibliografia
https://pbiecek.github.io/NaPrzelajDataMiningR/part-3.html#part_31<br>
http://keii.ue.wroc.pl/clusterSim/clusterSim.pdf<br>
https://compgenomr.github.io/book/clustering-grouping-samples-based-on-their-similarity.html<br>
WYBRANE TESTY STATYSTYCZNE DLA WARTOŚCI NIETYPOWYCH I ICH ZASTOSOWANIE W ANALIZACH EKONOMETRYCZNYCH,Dorota Pekasiewicz<br>
www.rdocumentation.org<br>

