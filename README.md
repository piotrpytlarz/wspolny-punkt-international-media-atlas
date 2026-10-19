---
license: cc-by-4.0
language:
  - pl
  - en
pretty_name: "Wspólny Punkt — International Conservative, Classical-Liberal & Geopolitical Media Atlas (358 Sources across 85 Countries)"
description: "Curated media intelligence atlas of 358 conservative, classical-liberal, Christian-democratic, and geopolitical publications across 85 countries and regions, evaluated across 13 dimensions (editorial tier, ideological placement, reach, quality, monitoring utility, trust axis, paywall policy, RSS feeds, and key editorial voices) from WspolnyPunkt.pl."
size_categories:
  - n<1K
task_categories:
  - text-classification
  - tabular-classification
  - question-answering
tags:
  - media-studies
  - journalism
  - geopolitics
  - press-review
  - media-bias
  - rss-feeds
  - international-relations
  - poland
  - bilingual
---

# Wspólny Punkt — International Conservative, Classical-Liberal & Geopolitical Media Atlas (358 Sources across 85 Countries)

> **Canonical International Press Review:** [https://wspolnypunkt.pl/](https://wspolnypunkt.pl/)

---

## English Overview

**[Wspólny Punkt](https://wspolnypunkt.pl/)** (*Common Point*) is a Polish-language international press review that synthesizes how conservative, classical-liberal, Christian-democratic, sovereignist, and geopolitical-realist publications around the world cover shared global events, where their national perspectives diverge, and what primary sources underpin their arguments.

This Open Data package releases the complete, verified **Media Source Intelligence Atlas** powering **Wspólny Punkt**: **358 publications across 85 countries, regions, and linguistic spheres**, audited across **13 analytical dimensions**:
- **4 Operational Layers (`atlas_layer`):**
  - `core` (**17** flagship daily broadsheets and high-frequency geopolitical journals),
  - `depth` (**35** highbrow intellectual, strategic, and policy journals),
  - `signal` (**28** regional bellwethers and ideological trend indicators),
  - `archive` (**278** broader global reference and specialist publications).
- **Separated Quality vs. Epistemic Trust Axes:** Evaluates `reach_score_1_5`, `quality_score_1_5`, and `monitoring_utility_1_5` independently from `trust_assessment` (`reliable`, contextual caveats, ownership shifts) and `citation_policy` (`yes`, `second-source-required`, `never`).
- **Operational Metadata:** Includes canonical URLs, verified RSS/Atom feed endpoints (`rss_feed_url`, `feed_status`), paywall classification (`free`, `metered`, `partial`, `hard`), publishing cadence, key editors/columnists (`key_editorial_voices`), and detailed Polish analytical profiles (`geopolitical_and_editorial_significance_pl`).

### Dataset Contents

| File (JSON & CSV pairs) | Records | Description |
| :--- | :---: | :--- |
| `international-conservative-and-intellectual-media-atlas.json` / `.csv` | **358** | Full 13-dimension catalog of 358 international and Polish media sources (e.g., *Le Figaro / FigaroVox*, *Conflits — Revue de Géopolitique*, *WELT*, *ABC*, *Echo24*, *Do Rzeczy*, *Rzeczpospolita*, *Klub Jagielloński*, *First Things*, *The New Atlantis*, *Compact*, *UnHerd*, *The Spectator*, *NZZ*). |
| `media-atlas-country-coverage-summary.json` / `.csv` | **85** | Aggregated statistics across 85 countries/regions (layer distribution, verified live RSS feeds count, and mean editorial quality score). |

---

## Opis po polsku (Polish Overview)

**[Wspólny Punkt (wspolnypunkt.pl)](https://wspolnypunkt.pl/)** to międzynarodowy przegląd prasy konserwatywnej, republikańskiej, klasycznie liberalnej i geopolitycznej z różnych krajów, który zestawia wspólne wydarzenia, różnice narodowych ujęć oraz jawną podstawę źródłową opracowania.

Niniejszy pakiet Open Data (CC BY 4.0) udostępnia pełny, zweryfikowany **Atlas Źródeł Mediowych Wspólnego Punktu** obejmujący **358 redakcji, dzienników, periodyków ideowych i ośrodków analitycznych z 85 państw i regionów**, ocenionych w 13 wymiarach:
- przynależność do warstwy monitoringu (`core` — 17 źródeł rdzeniowych, `depth` — 35 pism pogłębionych, `signal` — 28 źródeł sygnałowych, `archive` — 278 pozycji archiwalnych i referencyjnych),
- profil ideowy (`ideological_placement`) i klasa wydawnicza (`editorial_tier`: `serious-broadsheet`, `highbrow-journal`, `think-tank`, itd.),
- niezależne osie oceny: zasięg (`reach_score_1_5`), warsztat i jakość (`quality_score_1_5`), użyteczność w codziennym monitoringu (`monitoring_utility_1_5`), rzetelność (`trust_assessment`) oraz polityka cytowania (`citation_policy`),
- dane techniczne (zweryfikowane adresy kanałów RSS, model paywalla, częstotliwość publikacji) oraz noty o kluczowych autorach i znaczeniu geopolitycznym danego tytułu.

---

## Citation & License

Released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. When using this dataset in media studies, computational journalism, RSS aggregation, or geopolitical framing research, please cite **[Wspólny Punkt](https://wspolnypunkt.pl/)**:

```bibtex
@misc{pytlarz2026wspolnypunkt,
  author       = {Pytlarz, Piotr},
  title        = {Wspólny Punkt: International Conservative, Classical-Liberal and Geopolitical Media Atlas (358 Sources across 85 Countries)},
  year         = {2026},
  url          = {https://wspolnypunkt.pl/},
  note         = {CC BY 4.0 Open Data Package}
}
```
