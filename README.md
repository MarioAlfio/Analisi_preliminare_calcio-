# Analisi_preliminare_calcio

Ho costruito il mio database considerando alcune informazioni per ogni attaccante dal sito fbref.com, dalla stagione 2017/2018 alla stagione 2021/2022.
Si suddivide in 6 categorie per un totale di 403 osservazioni e 33 variabil

Le categorie sono le seguenti:

1.	Info generali sul giocatore
1.	Minuti giocati
1.	Prestazione generali: comprende numero goal, assist, rigori sbagliati, rigori realizzati, rigori tentati e cartellini gialli e rossi.
1.	Prestazioni nei 90 minuti
1.	Gli expected per le prestazioni generali 
1.	E infine, gli expected nelle prestazioni nei 90 minuti

Analisi preliminare:

1.	ho eliminato le variabili riguardanti squadra, nazionalità e anno di nascita (con le quali ho intenzione di svolgere altre analisi)
1.	controllato se ci fossero dati mancanti
1.	trasformo la colonna Player da variabili stringa a variabili numeriche in modo da facilitare i calcoli al modello
1.	Costruito grafico di correlazione più ci si avvicina al verde più le variabili sono correlate tra loro, variabili con correlazione nulla avranno colore quasi vicino     al bianco; variabili con correlazione inversa avranno colore tendente al rosa/porpora.
1.	Costruzione heatmap
1.	Considero le variabili più correlate tra loro
