# CompositeSectionCheck

Il framework definitivo e interattivo per il calcolo, l'omogeneizzazione e la verifica di sezioni composte acciaio-calcestruzzo.

👉 **[Guarda la Demo Interattiva Web](https://domenicogaudioso.github.io/CompositeSectionCheck/)** 👈

## Funzionalità
- **Motore di Omogeneizzazione**: Calcolo del rapporto modulare $n$, sezione reagente e inerzia.
- **Verifiche NTC2018 / EC4**: SLU, SLE, taglio, flessione e interazione M-N-V.
- **Fasi Costruttive**: Analisi automatica pre e post-getto, effetti reologici.
- **CLI Integrata**: Genera e verifica profili da riga di comando.

## Installazione
```bash
npm install -g compositecheck
compositecheck init --project "ponte-fiume"
compositecheck add-profile --type HEA400 --grade S355
compositecheck add-slab --t 250 --w 3000 --concrete C30/37
compositecheck verify --code NTC2018
