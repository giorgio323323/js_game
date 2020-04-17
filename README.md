# js_game

questi file sono esercizi per serate a StuffCube.

Il file "mio.html" permette di muovere una palla sullo schermo usando la tastiera.

Come è possibile che due giocatori da remoto possano ognuno muovere la propria palla e condividere il campo da gioco?



io ho fatto una prova con MQTT e il broker [HIVE](http://www.hivemq.com/demos/websocket-client/

). 
Ogni pc (client) esegue lo script (uno mio_mqttA e uno mio_mqttB. pubblica quando c'è un evento tastiera teta, vel, x, y e sottoscrive gli altrui. Una pallina per ogni client gira in base a questi messaggi. 
Quello che si vede è che all'arrivo del messaggio la x e y torna indietro un attimo. le x e y sono quelle di origine e non c'è il tempo di tx. 
Voglio verificare se il timestamp alla trasmissione mi permette di calcolare il tempo di viaggio.

