# Subnetting di 4 sottoreti
Il subnetting è una tecnica utilizzata per suddividere una rete IP in sotto-reti più piccole, consente di ottimizzare l'utilizzo degli indirizzi IP, ridurre il traffico di rete e migliorare le prestazioni complessive della rete stessa.

Nel caso specifico di una rete IP che prevede la creazione di 4 sotto-reti, il primo passo consiste nell'assegnare un blocco di indirizzi IP alla rete. Questo blocco può essere rappresentato da una serie di numeri separati da punti, come ad esempio 192.168.1.0/24, dove il valore 24 rappresenta il numero di bit che vengono utilizzati per definire la maschera di rete.

* Per suddividere il blocco di indirizzi in 4 sotto-reti, è necessario utilizzare una maschera di sottorete che permetta di definire la dimensione di ogni sotto-rete. In questo caso, la maschera di sottorete dovrebbe avere almeno 2 bit aggiuntivi rispetto alla maschera di rete originale per consentire la creazione di 4 sotto-reti. Quindi, la maschera di sottorete diventa 255.255.255.192, che corrisponde a una lunghezza di prefisso di 26 bit.

* Con questa nuova maschera di sottorete, la rete IP può essere suddivisa in 4 sotto-reti di dimensioni uguali. L'indirizzo di rete per ciascuna sotto-rete può essere calcolato applicando la maschera di sottorete all'indirizzo di rete originale. Ad esempio, se l'indirizzo di rete originale è 192.168.1.0, i primi 26 bit dell'indirizzo rappresentano l'indirizzo di rete e gli ultimi 6 bit rappresentano gli indirizzi host disponibili in ogni sotto-rete.

* Quindi, le 4 sotto-reti avranno gli indirizzi di rete 192.168.1.0, 192.168.1.64, 192.168.1.128 e 192.168.1.192. Ognuna di queste sotto-reti potrà ospitare fino a 62 dispositivi, dal momento che 2 degli 64 indirizzi host disponibili in ogni sotto-rete saranno riservati per l'indirizzo di rete e l'indirizzo di broadcast.

Il subnetting di 4 sotto-reti consente di ottimizzare l'utilizzo degli indirizzi IP, evitando così il rischio di esaurimento degli indirizzi disponibili. Inoltre, la suddivisione della rete in sotto-reti più piccole consente di migliorare le prestazioni della rete, riducendo il traffico di broadcast e migliorando la sicurezza complessiva della rete stessa.

