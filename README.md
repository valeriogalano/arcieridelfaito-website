# Arcieri del Faito - Sito Web

[Arcieri del Faito](https://valerioglaano.github.io/arcieridelfaito-website) è un sito web creato per l'associazione Arcieri del Faito. Il
sito è costruito utilizzando [Hugo](https://gohugo.io/) ed è ospitato su GitHub Pages.

## Struttura del Progetto

- **content/**: Contiene i file di testo (file Markdown) che Hugo convertirà in HTML.
- **layouts/**: Template di layout personalizzati per il tuo sito.
- **static/**: Contiene le immagini da utilizzare nel sito
- **config.toml**: Il principale file di configurazione per il sito Hugo.

## Installazione

Per configurare questo progetto in locale, segui questi passaggi:

1. **Clona il repository:**
    ```sh
    git clone https://github.com/valeriogalano/arcieridelfaito-website.git
    cd arcieridelfaito-website
    ```

2. **Installa Hugo:**
   Assicurati di avere Hugo installato. Se non è installato, segui le istruzioni
   sulla [pagina ufficiale di installazione di Hugo](https://gohugo.io/getting-started/installing/).

3. **Avvia il sito localmente:**
   Una volta installato Hugo, puoi eseguire il progetto localmente:
    ```sh
    hugo server
    ```

   Di default, il sito dovrebbe essere accessibile a `http://localhost:1313`.

## Come Contribuire

Accogliamo con favore i contributi per migliorare o correggere questo sito! Puoi controllare nella sezione [Issues](https://github.com/valeriogalano/arcieridelfaito-website/issues) se vuoi aiutare a svolgere qualche attività in sospeso.

Segui questi passaggi per contribuire al progetto:

1. **Forka il repository:**
   Clicca sul pulsante "Fork" in alto a destra nella pagina del repository per creare una copia del repository sotto il
   tuo account GitHub.

2. **Clona il tuo repository forkato:**
    ```sh
    git clone https://github.com/YOUR-USERNAME/arcieridelfaito-website.git
    cd arcieridelfaito-website
    ```

3. **Crea un nuovo branch:**
   Crea un nuovo branch per le tue modifiche e passa a quel branch:
    ```sh
    git checkout -b your-feature-branch
    ```

4. **Fai le tue modifiche:**
   Apporta le necessarie modifiche nel tuo branch.

5. **Committa le tue modifiche:**
    ```sh
    git add .
    git commit -m "Descrivi le tue modifiche"
    ```

6. **Push delle tue modifiche:**
   Effettua il push delle tue modifiche sul tuo fork:
    ```sh
    git push origin your-feature-branch
    ```

7. **Crea una Pull Request:**
   Vai al repository originale e clicca sul pulsante "New Pull Request". Specifica il branch dal quale vuoi unire le tue
   modifiche e descrivi le tue modifiche.

Revisioneremo la tua pull request e forniremo feedback. Una volta approvate le tue modifiche, verranno unite nel branch
principale.

Grazie per aver contribuito!