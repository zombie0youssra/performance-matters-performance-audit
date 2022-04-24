
# Performance Matters - Performance Audit

Leren hoe je een Performance Audit doet en documenteert.

## Context

Deze leertaak hoort bij sprint 10 Performance Matters. Dit is een deeltaak die je individueel uitvoert.

In het college S10W1-01-Kickoff-Performance-Matters wordt behandeld wat Performance is en hoe je een Performance Audit doet.

## Doel van deze opdracht

Één van de mooiste [principes](https://www.w3.org/DesignIssues/Principles.html) van het web is dat iedereen met een computer en een browser het web kan gebruik. [Het web is voor iedereen](https://www.youtube.com/watch?v=UMNFehJIi0E). 

Performance is daar een belangrijk onderdeel van. _Performance == Accessibility_ zegt Léonie Watson. 

In deze opdracht ga je leren een Performance Audit te doen met Lighthouse, een open-source tool om websites te testen en verbeteren. 

## Werkwijze

Opdracht: Doe een Performance Audit op een bestaande website. Gebruik Lighthouse om de Audit te doen en documenteer de bevindingen en wat zou kunnen worden verbeterd. 

![image](https://user-images.githubusercontent.com/1391509/164995178-253d9639-3950-44ce-a765-914a4b95a945.png)

Deze opdracht gaat over de [analyse](#analyse) fase van de DLC.

### Analyse
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*

<details>
<summary>Aanpak</summary>


1. Open Dev Tools in Google Chrome en run een Lighthouse Performance Audit.
2. Analyseer de Metrics:
    - First Contentful Paint (FCP)
    - Largest Contentful Paint (LCP)
    - First Input Delay (FID)
    - Time to Interactive (TTI)
    - Total Blocking Time (TBT)
    - Cumulative Layout Shift (CLS)
3. Bekijk welke _Opportunities_ en _Diagnostics_ zijn gevonden.
4. Schrijf per Metrics wat je hebt gevonden en hoe dit kan worden verbeterd als de score onder de 90 is.

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

