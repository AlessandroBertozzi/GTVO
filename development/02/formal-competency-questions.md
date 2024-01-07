# Formal Competency Questions

## CQ_2.1
Return the ID of the `term_a`.

```
PREFIX gtvo: <https://gotriple.eu/ontology/triple/gtvo#>
PREFIX datacite: <http://purl.org/spar/datacite/>

SELECT ?id WHERE {
  gtvo:term_a datacite:hasIdentifier ?id .
}
```

## CQ_2.2
Return all the ids of the terms inside the `vocabulary_a`.

```
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX gtvo: <https://gotriple.eu/ontology/triple/gtvo#>
PREFIX datacite: <http://purl.org/spar/datacite/>

SELECT ?ids WHERE {
  ?terms skos:inScheme gtvo:vocabulary_a .
  ?terms datacite:hasIdentifier ?ids
}
```
