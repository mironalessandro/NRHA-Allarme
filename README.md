NRHA-Allarme
============

Gestione dell'allarme

### About

This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.

### Cosa fa

Questo flow gestisce l'allarme di casa con dei sensori porte/finestre e presenza Xiaomi. Inoltre viene gestita anche una cassaforte con un sensore di vibrazione sempre XIAOMI.
Il tutto viene gestito tramite dei device tracker per permettere l'attivazione e la disattivazione dell'allarme in automatico. Viene gestito a parte un 3 device tracker chiamato nonna che è al di fuori della famiglia quindi anche il comportamento è diverso in quanto limitato.

Come "sirena" viene usata una vera e propria sirena e Alexa tramite TTS. Inoltre alexa ha un TTS attivato in base a degli orari solamente per quanto riguarda l'inserimento ed il disinserimento dell'allarme.

### Requisiti

I requisiti sono alcune variabili che vanno personalizzate in base alle vostre necessità ed il componente sensor.time_online per evitare inserimenti anomali dopo un riavvio di HA.

