Codice gruppo: vz94k020jtk
Componenti gruppo: 2
Nome partecipanti: Lorenzo Pelliccia 0124002578
                   Pierluca Landolfi 0124002709

            Traccia Torrent:
    Progettare una rete P2P con protocollo TCP che simula lo scambio file utilizzata da torrent.

Ci sono n peers (n > 2) che mettono a disposizione un file di testo (tutti i peers hanno lo stesso file) nel momento in cui un nuovo peers entra nella rete e richiede il file questo deve essere inviato da tutti i peers che hanno a disposizione quel file. 
Ogni peers invia una sottoporzione del file, per semplicità è necessario dividere la lunghezza del file per il numero di peers che hanno il file.
Es.

3 peers hanno il file
I peers avranno id: 1, 2, 3
La dimensione del file viene divisa per 3 arrotondando il numero di bytes da trasmettere
filesize 1024mb / 3 = 341,33
Peer 1 invia 341 bytes
Peer 2 invia 341 bytes 
Peer 3 invia 342 bytes


Aggiungere un server tracker che invia la lista dei peers che hanno il file.


            
