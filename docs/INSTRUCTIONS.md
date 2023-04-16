
# Performance Matters - Performance Audit

Doe een Performance Audit op een bestaande website en documenteer je bevindingen.

## Context

Deze deeltaak hoort bij sprint 10 Performance Matters. Dit is een dedeltaak die je individueel uitvoert.

In het college S10W1-02-Frontend-Performance-Audit wordt behandeld wat _performance_ is en hoe je een Performance Audit doet.


## Doel van deze opdracht

Één van de mooiste [principes](https://www.w3.org/DesignIssues/Principles.html) van het web is dat iedereen met een computer en een browser het web kan gebruik. [Het web is voor iedereen](https://www.youtube.com/watch?v=UMNFehJIi0E). 

_Performance_ is daar een belangrijk onderdeel van. _Performance == Accessibility_ zegt [Léonie Watson](https://tink.uk/about-leonie/). 

In deze opdracht ga je leren een Performance Audit te doen met PageSpeed Insights, een open-source tool om de performance van websites te testen en te verbeteren. 

## Werkwijze

Opdracht: Doe een Performance Audit op een bestaande website. Gebruik PageSpeed Insights om de audit (test/beoordeling) te doen en documenteer de bevindingen en wat zou kunnen worden verbeterd. 


Deze opdracht gaat over de [analyse](#analyse) fase van de DLC.

### Analyse

Voor deze opdracht doe je een analyse op een bestaande website. Kies een bestaande website om een Performance Audit voor te doen. Het is interessant om een website te analyseren die niet goed _performed_. Eerst doe je een audit en daarna ge je bekijken hoe de performance zou kunnen worden verbeterd. Na de analyse documenteer je je bevindingen in de Wiki. 


1. Ga naar [PageSpeed Insights](https://pagespeed.web.dev)
2. Vul de url in van de website waarvan je de performance wil testen en klik op _Analyze_
3. Kopieer, als de analyse klaar is, de link naar de resultaten van de analyse ('Copy link'-button rechtsbovenaan de pagina) en vermeld de link bij je documentatie in de Wiki van de leertaak
4. Analyseer deze Metrics:
    - Largest Contentful Paint (LCP)
    - Cumulative Layout Shift (CLS)
    - First Contentful Paint (FCP)
    - Speed Index (SI)
    - Total Blocking Time (TBT)
5. Lees per metrics wat het is, wat het meet en hoe je het zou kunnen verbeteren
    - Kik _Learn more_ in de PageSpeed Insights  rapprt bij de Metrics
6. Bekijk welke _Opportunities_ en _Diagnostics_ zijn gevonden
7. Documenteer per Metrics wat je hebt gevonden en hoe dit kan worden verbeterd

#### Bronnen analysefase

- [PageSpeed Insights](https://pagespeed.web.dev)
- [Metrics - Measuring performance and user experience](https://web.dev/metrics/)
- [Web Performance](https://developer.mozilla.org/en-US/docs/Web/Performance)

## Criteria

Focus sprint 10 - De focus van deze sprint ligt op het beter en sneller laten werken van een applicatie.

Deze leertaak hoort bij het gedragscriterium:

P: Je analyseert een vraag, signaleert knelpunten ~~en volgt de aangeboden oplossingsrichting~~.

Deze opdracht is done als:

- [ ] Er is met PageSpeed Insights een Performance Audit van een bestaande website gedaan
- [ ] Het onderzoek is gedocumenteerd in de Wiki van de leertaak
