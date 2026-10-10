Gestore Ricevute Prestazione Occasionale

Applicazione Web standalone responsive per il calcolo avanzato, la creazione e la gestione di ricevute per prestazioni occasionali con Ritenuta d'Acconto e ricarico/scorporo IRPEF personalizzato.

L'applicazione è progettata per lavoratori autonomi e privati che prestano opera occasionale a favore di ditte, aziende o titolari di Partita IVA, e necessitano di calcolare esattamente l'importo lordo partendo dall'incasso netto desiderato.

🌟 Caratteristiche Principali

Calcolo Dinamico Reale vs Lordo:

Integrazione Aliquota IRPEF (es. 35%): Calcola il prezzo lordo da fatturare partendo dal compenso netto effettivo desiderato in tasca.

Ritenuta d'Acconto (20%): Applicazione automatica della ritenuta d'acconto fiscale sulle prestazioni svolte.

Marca da Bollo (€ 2,00): Rilevamento automatico per importi superiori a € 77,47 con opzione di addebito al committente o carico al lavoratore.

Gestione Voci e Tabella Servizi:

Inserimento dinamico di descrizioni, quantità e prezzi unitari con aggiornamento immediato di tutti i totali.

Anagrafica Completa:

Sezioni dedicate per i dati del Mittente (Privato), del Committente (Azienda) e per le Info del Documento (Numero, Data, Oggetto, IBAN e Modalità di pagamento).

Anteprima Live A4:

Layout grafico professionale pronto per la stampa con diciture legali e fiscali di default (Art. 2222 C.C. ed esenzione IVA ex Art. 5 DPR 633/72).

Esportazione & Stampa:

Generazione e download diretto del file PDF tramite la libreria html2pdf.js.

Funzione di stampa integrata ottimizzata per foglio A4.

Archivio Locale (Privacy First):

Salvataggio e caricamento dei documenti tramite localStorage del browser, senza inviare alcun dato a server esterni.

🚀 Come Utilizzare l'Applicazione

Non è richiesta alcuna installazione o configurazione di server.

Scarica o clona il progetto sul tuo computer.

Apri il file index.html in un qualsiasi browser moderno (Chrome, Firefox, Edge, Safari).

Compila i campi:

Imposta l'aliquota IRPEF di riferimento (es. 35%) e la modalità di calcolo.

Inserisci i dati del Mittente e del Committente.

Aggiungi i servizi svolti nella sezione Voci e Prestazioni.

Verifica l'anteprima live del documento nel riquadro di destra.

Clicca su Scarica PDF per salvare la ricevuta sul computer oppure su Salva Documento per conservarla nell'archivio del browser.

🧮 Logica di Calcolo Fiscale

1. Da Incasso Reale Desiderato (Modalità Ricarico IRPEF)

Se desideri ricevere un importo netto $N$ (es. € 500,00) garantendoti la copertura dell'aliquota IRPEF personale del 35%:

$$\text{Compenso Lordo} = N \times (1 + \text{Aliquota IRPEF})$$

$$\text{Ritenuta d'Acconto (20\%)} = \text{Compenso Lordo} \times 0.20$$

$$\text{Netto a Saldo Spettante} = \text{Compenso Lordo} - \text{Ritenuta d'Acconto} (+ \text{Bollo se addebitato})$$

2. Prezzo Lordo Diretto

Il valore inserito viene considerato direttamente come imponibile fiscale su cui calcolare la Ritenuta d'Acconto del 20%.

🛠️ Tecnologie Utilizzate

HTML5 & JavaScript (ES6+): Logica applicativa reattiva senza framework pesanti.

Tailwind CSS: Styling moderno, responsivo e ottimizzato tramite CDN.

Lucide Icons: Icone SVG leggere e pulite.

html2pdf.js: Generazione vettoriale del PDF del documento.

⚖️ Note Legali

Il documento generato include le diciture standard previste dalla normativa italiana per le prestazioni occasionali:

Operazione fuori campo di applicazione IVA ai sensi dell'art. 5 del D.P.R. 633/1972.

Prestazione svolta ai sensi dell'art. 2222 e segg. del Codice Civile.

Esenzione dall'obbligo d'iscrizione alla Gestione Separata INPS nei limiti del soffitto annuale di € 5.000,00 (art. 44 D.L. 269/2003).
