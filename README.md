# AMMS-Specs
Specifiche del sistema AMMS.

## Pool feature da mantenere/aggiungere

### Connettività Internet

#### Wi-Fi

Le stazioni possono connettersi ad una rete Wi-Fi. Prevedere la possibilità di aggiungere una rete secondaria di fallback. Nel caso il segnale della rete primaria scendesse sotto il threshold configurato, la stazione effettuerà il roaming alla rete secondaria se possibile.

#### Ethernet

Prevedere la connettività ethernet.

#### Access point locale

Prevedere la configurazione per l'accesso tramite access point locale.

### Invio letture dei sensori

Le stazioni possono inviare i dati dei sensori abilitati. Prevedere la configurazione di parametri specifici ad ogni sensore come i PIN per la connessione.

#### Cloud AMMS

Le stazioni possono inviare i dati al server centrale AMMS tramite diversi protocolli.

#### Server MQTT personale

Le stazioni possono inviare i dati ad un server MQTT definito dall'utente.

### Controllo I/O

Prevedere il controlo di I/O tramite routine, automazioni e controlli manuali locali o remoti.

### Configurazione

Tutte le configurazioni e i controlli avverrano tramite [JSON-RPC 2.0](https://mongoose-os.com/docs/mongoose-os/userguide/rpc.md).