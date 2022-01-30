# Progetto_grafo
Partendo da un dataset di città, l'obiettivo di questo codice è quello di creare un grafo in cui una città si colleghi con le 3 città più vicine. L'utente dovrà inserire l'id di due città e/o il codice iso2 di uno stato a piacere. Verrà calcolato e disegnato (in verde) il tragitto più breve (che passa per il minor numero di nodi) tra le due città utilizzando il grafo indiretto. Utilizzando il grafo diretto, invece, verrà calcolato, con buona accuratezza, uno dei tragitti più lunghi tra due città della stessa nazione scelta. In questo caso i nodi saranno di colore blu. Infine, per entrambi i tragitti verrà calcolata la durata in ore secondo i seguenti criteri: -sono necessarie 2 ore per passare alla città più vicina, 4 ore per la seconda e 8 per la terza; -sono necessarie 16 ore se si passa ad una città che non è tra le tre più vicine (solo nel caso del grafo indiretto); -sono necessarie 2 ore aggiuntive se si passa in un altro stato e altre 2 se si passa ad una città con una popolazione maggiore di 200000.
