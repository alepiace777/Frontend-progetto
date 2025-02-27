<div style="display: flex; align-items: center;">
  <img src="images/logo.png" width="180" style="margin-right: 10px;">
  <h1 style="font-size: 36px; font-weight: bold; margin: 0;">TogetherTicket</h1>
</div>

**CacioKart** è un sito web dove è possibile, dal lato utente, prenotare e acquistare kart, visualizzare le classifiche dei migliori piloti e, nella sezione del profilo personale, consultare il proprio miglior tempo e prenotare gare libere.

---

## Ruoli e Funzionalità

All'interno dell'applicazione, sono presenti **5 dipendenti** con ruoli specifici:

1. **Meccanico**  
   - Aggiungere nuovi kart all’autodromo  
   - Visualizzare ed eventualmente eliminare i kart esistenti  
   - Aggiungere benzina ai kart e gestire la manutenzione

2. **Gestore della concessionaria**  
   - Aggiungere i kart  
   - Aggiungere i pezzi di ricambio per i kart

3. **Arbitro**  
   - Visionare le gare secche (gare singole)  
   - Aggiungere penalità, se necessario

4. **Organizzatore**  
   - Creare dei team e le gare secche  
   - Aggiungere le persone che parteciperanno a tali gare  
   - Creare e gestire un campionato

5. **Proprietario**  
   - Aggiungere o eliminare dipendenti  
   - Visionare il bilancio

---

## Tecnologie Utilizzate

![Frontend](https://img.shields.io/badge/Frontend-HTML-E34F26?style=for-the-badge&logoColor=white)  ![Java](https://img.shields.io/badge/Backend-Java-007396?style=for-the-badge&logo=java&logoColor=white)   ![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  ![Eclipse](https://img.shields.io/badge/IDE-Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)  



- **PHP/Javascript/HTML/CSS**: Frontend per l'interfaccia utente.
- **Java**: Backend per la gestione delle operazioni, come l'autenticazione, la gestione degli eventi.
- **MySQL WorkBench**: Database per la memorizzazione tutti i possibili dati.
- **IntelliJ IDEA Community**: IDE utilizzato per lo sviluppo del progetto.

## Prerequisiti

Per eseguire questo progetto sul proprio dispositivo, è necessario avere:

- **Git**: Per usare il comando git nel prompt dei comandi. Puoi scaricarlo [qui](https://git-scm.com/downloads/win)
- **Java Development Kit (JDK) 11 o superiore**: Assicurati di avere Java installato. Puoi scaricarlo da [qui](https://www.oracle.com/java/technologies/downloads/#jdk23-windows).
- **MySQL WorkBench**: Per la gestione del database. Puoi scaricarlo da [qui](https://dev.mysql.com/downloads/installer/).
- **IntelliJ IDEA Community***: Un IDE per lo sviluppo Java. Puoi scaricarlo da [qui](https://www.jetbrains.com/idea/download/?source=post_page---------------------------&section=windows)

## Configurazione del progetto

1. **Clona il repository**: Nel prompt dei comandi digita:

   ```bash
   git clone https://github.com/IngSW-unipv/Progetto-I25.git

3. **Configura il database**:
   -Si esegue uno script per creare il database con tutte le tabelle chiamato CreaDB.sql
   -Si esegue uno script per popolarlo chiamato PopolaDB.sql

4. **Importa il progetto in IntelliJ**:
   - Apri IntelliJ e seleziona `File > Open >
   - Seleziona la cartella del progetto `Progetto-I25` che hai clonato.
  
5. **Cambia password di MySQL**:
   - Apri workbench e inserisci questa stringa:
   ALTER USER 'root'@'localhost' IDENTIFIED BY '';

6. **Configurazione del server XAMPP**:
   - Aprire XAMPP andare in APACHE seleziona Config > Apache(httpd.conf)
   - Nel documento trovare DocumentRoot e Direcoty, cambiare il percorso con il percorso del sito web
   - Se non e' presente scaricalo [qui](https://www.apachefriends.org/download.html).
   - Avviare il Apache

7. **Avvio dell'applicazione**:
   - Avvia il server Apache tramite XAMPP
   - Avviare il main del codice da IntelliJ IDEA
   - Accedi all'applicazione nel browser visitando `http://localhost/`.

---

## Come utilizzare CacioKart**

### Registrazione e login

- Vai alla pagina di **login** per accedere al sistema se hai già un account.
- Se sei un nuovo utente, vai alla pagina di **registrazione** per creare un nuovo account. Una volta registrato, sarai automaticamente loggato.
- Esempi di credenziali:
```bash
        username: Admin1      password: 12345678              username: Andrea       password: 12345678
ADMIN   username: Admin2      password: 12345678   UTENTE     username: Alessandro   password: 12345678
        username: Admin3      password: 12345678              username: Luca         password: 12345678
		username: Admin4      password: 12345678   UTENTE     username: Davide       password: 12345678
        username: Admin5      password: 12345678              username: Adriano      password: 12345678
```
