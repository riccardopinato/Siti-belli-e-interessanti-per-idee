# Tassonomia e procedura di catalogazione

Questo repository consente **più categorie per sito**: una categoria principale e categorie secondarie. La classificazione riflette cosa si può apprendere dal sito, non soltanto il settore commerciale.

| Categoria | Quando usarla |
|---|---|
| \`open-source-discovery\` | Directory OSS, cataloghi GitHub, raccolte di librerie, progetti e API |
| \`design-ui-ux\` | Interfacce, interaction design, pattern, tipografia, identità visiva |
| \`motion-storytelling\` | Transizioni, animazioni, scrollytelling, narrazione visuale |
| \`ai-creativity\` | Uso creativo, progettazione o riflessione sull'intelligenza artificiale |
| \`development-tools\` | Strumenti, framework, SDK, supporto allo sviluppo e automazione |
| \`product-inspiration\` | Problemi, flussi, idee di prodotti o modelli di esperienza |
| \`learning-resources\` | Guide, documentazione, articoli formativi, corsi |
| \`research-data\` | Dataset, statistiche, motori di ricerca e analisi |
| \`business-growth\` | SEO, distribuzione, marketing, monetizzazione |
| \`other\` | Nuova tipologia non ancora in tassonomia: descrivere il motivo |

## Come registrare un link futuro

1. Normalizzare l'URL (host, \`https\`, slash finale) ed evitare duplicati o versioni con parametri di tracciamento.
2. Aprire il sito originale; se inaccessibile, annotare chiaramente **cosa è verificato e cosa no**.
3. Assegnare un ID stabile \`SITE-000\`, titolo, breve descrizione, categoria principale, categorie secondarie e tag.
4. Registrare **perché è interessante per App Factory** e a quali app/repository potrebbe servire; distinguere fatti osservati da ipotesi.
5. Creare o aggiornare una scheda in \`schede/\`, aggiungere la riga all'indice e aggiornare \`catalogo/siti.json\`.
6. Le immagini nel repository devono essere originali oppure avere permessi/licenza compatibili. Se manca una verifica dei diritti, utilizzare **copertine originali** o un semplice link al sito esterno; non copiare screenshot/asset alla cieca.
7. Aprire PR, verificare URL, JSON, file referenziati e differenze rispetto all'indice; registrare l'esito reale.

## Stati del catalogo

- **archiviato-verificato**: sito e funzione generale riscontrati in fonte primaria o documentazione affidabile.
- **archiviato-parziale**: una parte della scheda è stata ricostruita da fonti secondarie perché la pagina non era completamente accessibile.
- **da-rivedere**: sito cambiato, link incerto, informazioni non confermate.
- **non-disponibile**: link non più raggiungibile, mantenuto per ragioni storiche.

Questi stati non equivalgono a \`IMPLEMENTED\`, \`TESTED\`, \`CERTIFIED DONOR\` o \`GOLDEN\`.

## Relazioni e priorità

**App Factory Core** determina policy e prove; il **catalogo siti** offre spunti. Il repository **Design-App** conserva il ruolo di archivio estetico preferenziale per gli elementi scelti dall'utente e realmente catalogati là. Un link di questo archivio non sovrascrive di per sé scelte di progetto già approvate.

Per donor, codice e componenti: controllare origine, licenze, licenze dei singoli asset, manutenzione, compatibilità, privacy, sicurezza e collaudo prima di riusare.
