# Motivating Scenario (Iteration 1)

## Name
Concept and vocabulary organization

## Description
The GoTriple platform is a data aggregator in the field of social sciences and humanities. As of January 2024, it gathers information from approximately 1300 different data sources. Given the vastness and diversity of these sources, there is a multitude of metadata available. For researchers, programmers, or general users, understanding the types and quantities of metadata available becomes almost impossible without a structured and organized vocabulary.

In addition to the challenge of knowing which entities can be utilized for research purposes, another issue is identifying which of these entities correspond to those more widely used and recognized. This necessitates connecting individual units contained in a vocabulary with units in other, more widely disseminated and authoritative vocabularies.

Within GoTriple, a vocabulary is defined as a list of terms at the same level, meaning there is no hierarchical structure between the various terms. Each term can be connected to other terms, including those outside the currently used vocabularies, through two types of relationships: closely related and exactly related.
## Example 1
`document_1` is classified as a `type_a`. The `type_a` type belongs to the `vocabulary_a` and is linked to the `term_456` entity on `Wikidata`.

## Example 2
`document_456` was published in the disciplinary field of `discipline_a`. `discipline_a` belongs to the `vocabulary_b` and is linked to the `discipline_a` entity on both `Wikidata` and the `Library of Congress`.