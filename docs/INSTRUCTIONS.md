
# Performance Matters - Performance Audit

Leren hoe je een Performance Audit doet en documenteert.

## Context

Deze leertaak hoort bij sprint 10 Performance Matters. Dit is een deeltaak die je individueel uitvoert.

In het college S10W1-01-Kickoff-Performance-Matters wordt behandeld wat _performance_ is en hoe je een Performance Audit doet.

## Doel van deze opdracht

Één van de mooiste [principes](https://www.w3.org/DesignIssues/Principles.html) van het web is dat iedereen met een computer en een browser het web kan gebruik. [Het web is voor iedereen](https://www.youtube.com/watch?v=UMNFehJIi0E). 

_Performance_ is daar een belangrijk onderdeel van. _Performance == Accessibility_ zegt Léonie Watson. 

In deze opdracht ga je leren een Performance Audit te doen met Lighthouse, een open-source tool om websites te testen en verbeteren. 

## Werkwijze

Opdracht: Doe een Performance Audit op een bestaande website. Gebruik Lighthouse om de audit (test/beoordeling) te doen en documenteer de bevindingen en wat zou kunnen worden verbeterd. 

<img width="1391" alt="image" src="https://user-images.githubusercontent.com/1391509/164996927-0f91670e-323c-4be2-8981-2bb95bf910b9.png">


Deze opdracht gaat over de [analyse](#analyse) fase van de DLC.

### Analyse

Voor deze opdracht doe je een analyse op een bestaande website. Kies een bestaande website om een Performance Audit te doen. Het is interessant om een website te analyseren die niet goed _performed_. Eerst doe je een audit en daarna ge je bekijken hoe de performance zou kunnen worden verbeterd. Na de analyse documenteer je je bevindingen in de Readme. 

<details>
<summary>Aanpak</summary>

1. Open Dev Tools in Google Chrome
2. Zet in de Network tab van de Dev Tools de chache uit en pas de netwerk snelheid aan:
    - Disable Cache
    - Network Throttle 3G
3. Run de Lighthouse Performance Audit
    - Klik _Generate Report_
4. Analyseer de Metrics:
    - First Contentful Paint (FCP)
    - Largest Contentful Paint (LCP)
    - First Input Delay (FID)
    - Time to Interactive (TTI)
    - Total Blocking Time (TBT)
    - Cumulative Layout Shift (CLS)
5. Bekijk welke _Opportunities_ en _Diagnostics_ zijn gevonden.
6. Schrijf per Metrics wat je hebt gevonden en hoe dit kan worden verbeterd als de score onder de 90 is. Of wat er goed gaat. 

#### Materiaal analysefase

- [Metrics - Measuring performance and user experience](https://web.dev/metrics/)
- [Web Performance](https://developer.mozilla.org/en-US/docs/Web/Performance)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)

</details>



## Criteria

Focus sprint 10 - De focus van deze sprint ligt op het beter en sneller laten werken van een applicatie.


Deze leertaak hoort bij het gedragscriterium:

P: Je analyseert een vraag, signaleert knelpunten ~~en volgt de aangeboden oplossingsrichting~~.

Deze opdracht is done als:

- [ ] Er is met Lighthouse een Performance Audit van een bestaande website gedaan
- [ ] Het onderzoek is gedocumenteerd in de Readme van de leertaak

