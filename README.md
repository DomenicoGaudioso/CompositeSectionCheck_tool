# CompositeSectionCheck_tool

Sito demo / landing page di **[CompositeSectionCheck](https://github.com/DomenicoGaudioso/CompositeSectionCheck)** — la suite per la verifica di sezioni composte acciaio-calcestruzzo per impalcati da ponte.

👉 **[Guarda la Demo Interattiva Web](https://domenicogaudioso.github.io/CompositeSectionCheck_tool/)** 👈

Il sito racconta, con simulazioni animate live (stile feagent), cosa fa la repo sorgente e le sue **tre famiglie di sezione**, una per branch:

| Famiglia | Caso singolo | Multi-sezione |
|---|---|---|
| Doppio T composto | [`Sezione-a-doppio-T`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/Sezione-a-doppio-T) | [`More-T-section`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/More-T-section) ⭐ riferimento |
| Doppio T irrigidito | [`Sezione-T-irrigidita`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/Sezione-T-irrigidita) | [`More-T-irrigidita`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/More-T-irrigidita) |
| Cassone | [`Cassone`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/Cassone) | [`More-Cassone`](https://github.com/DomenicoGaudioso/CompositeSectionCheck/tree/More-Cassone) |

## Contenuti del sito

- **CASE 01 · Fasi costruttive** — dalla trave nuda (G1) alla sezione trasformata post-getto, con n₀ / n∞ per fluage e ritiro, fino al comportamento fessurato: tensioni per fibra che evolvono fase per fase.
- **CASE 02 · Tre famiglie di sezione** — doppio T, T irrigidito (nervature piatto/T/canaletta, EN 1993-1-5 §4.5), cassone multi-anima con flusso torsionale q = Mt/(2·Am).
- **CASE 03 · Verifiche & report** — SLU flessione/taglio/interazione M-V, pioli Nelson, cordoni di gola, web breathing a fatica, relazione Word.
- Sezione **branch**, feature grid e guida all'installazione con elenco completo dei branch.

## Struttura

- `index.html` — pagina completa e autoconsistente (CSS + JS inline, animazioni canvas 2D + vista 3D three.js), nessuna build richiesta.

## Sorgente

Tutto il calcolo vive in **[DomenicoGaudioso/CompositeSectionCheck](https://github.com/DomenicoGaudioso/CompositeSectionCheck)** (moduli `SGMPy_*`, app Streamlit, export Excel/Word).
