# Twitch-Network-Analysis
Lo scopo di questo progetto è quello di sviluppare un’analisi originale di una rete sociale mettendo in pratica metodi, strumenti e tecniche di analisi e visualizzazione affrontati durante il corso “Social Network Analysis”.
Nel caso specifico di questo progetto, la ricerca è stata effettuata su una rete sociale composta da utenti portoghesi della piattaforma di streaming Twitch, ed i dati, risalenti al maggio 2018 e consistenti in due file .csv, sono stati scaricati dalla sezione “Stanford Network Analysis Project” (SNAP) dell’università di Stanford. All’interno della rete:

● i nodi rappresentano streamer portoghesi della piattaforma Twitch, e gli attributi associati riguardano le visualizzazioni totali ottenute, il periodo di attività (espresso in giorni), informazioni sull’età dello streamer (maggiorenne o meno) e sulle condizioni contrattuali con la piattaforma (partner o meno);

● gli archi rappresentano le amicizie tra gli streamer.
Il software che si è deciso di utilizzare per condurre l’analisi della rete è stato R, per la sua grande versatilità nell’analisi dei dati e, in particolare, per la presenza della libreria “igraph”, che permette analizzare e visualizzare grafi in maniera dinamica e non troppo complessa.

L'analisi prevede i seguenti step:
● visualizzazione della rete ed estrazione di informazioni utili;

● calcolo della centralità della rete attraverso diverse metriche;

● identificazione ed analisi di clusters ottenuti attraverso diversi algoritmi di community detection;

● misurazione di un eventuale fenomeno omofilia all’interno della rete rispetto agli attributi dei nodi.
