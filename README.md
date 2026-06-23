# RDF Knowledge Graph Construction for Geo Data

This project explores how to build an RDF knowledge graph from geographic data and use it to represent and query real-world geo entities such as countries, cities, airports, and their relationships.

## Project Goal

The main goal of this project is to transform geographic datasets into a structured semantic knowledge graph using RDF. By doing so, the data becomes easier to integrate, link, query, and reuse across different applications and research contexts.

In particular, the project focuses on:

- representing geo-related entities in RDF form
- organizing geographic knowledge into a graph structure
- connecting related entities through meaningful semantic relationships
- enabling SPARQL queries over the resulting knowledge graph
- supporting data alignment and ontology-based integration

## What’s Included

The repository contains grouped resources for different geographic domains, including:

- `airports/`
- `cities/`
- `countries/`
- `rdfs/`
- `alignement/`
- `queries/`

It also includes a report in french `Report.pdf` that documents the work and methodology behind the project.

## Example Query

The repository includes SPARQL queries such as:

- querying airports located in a specific city or country
- retrieving entities through RDF relationships
- testing the graph without alignment

## Why This Matters

Geo data is often distributed across multiple sources and formats. Converting it into RDF makes it more interoperable and semantically rich. This project demonstrates how knowledge graph construction can improve the way geographic information is modeled, queried, and reused.

## Technologies

- RDF
- SPARQL
- Knowledge Graphs
- Semantic Web concepts

## Output

The expected result of the project is a geo knowledge graph that can be queried semantically and extended with additional linked data sources.
