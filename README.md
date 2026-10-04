# Ravenwatch

**Ravenwatch** is an open-data project for collecting, structuring and analysing publicly available information on corruption cases, judicial proceedings and associated actors in Spain.

The project is designed to transform heterogeneous public records into reproducible, analysis-ready datasets that can be explored programmatically in R, used for statistical analysis and network research, and published as transparent datasets for platforms such as Kaggle.

Rather than treating corruption cases as isolated events, Ravenwatch focuses on their structure: cases, individuals, organisations, political and administrative roles, judicial status, temporal relationships and connections between actors. This makes it possible to study recurring patterns, institutional networks and the evolution of corruption cases over time.

The repository aims to provide a transparent and reproducible pipeline covering data acquisition, cleaning, normalisation, validation and dataset generation. Whenever possible, every observation is linked back to its original public source in order to preserve provenance and facilitate independent verification.

Ravenwatch does **not** determine guilt or make legal judgments. Judicial status, allegations, convictions, acquittals and other procedural outcomes are represented according to the terminology and information available in the underlying sources.

The name *Ravenwatch* is a deliberate nod to fantasy and science-fiction traditions in which watchers, ravens and sentinels act as observers and keepers of records. Here, the metaphor is simpler: watching public information carefully, preserving its provenance and making hidden structures easier to inspect.

## Goals

Ravenwatch is intended to support:

- reproducible analysis of corruption-related public data;
- longitudinal study of cases and judicial outcomes;
- analysis of relationships between individuals, organisations and institutions;
- construction of graph and network datasets;
- transparent publication of cleaned datasets;
- development of reusable R tools for data ingestion, validation and analysis.

The project prioritises **traceability, reproducibility and methodological neutrality** over interpretation.
