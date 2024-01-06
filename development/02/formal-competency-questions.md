# Formal Competency Questions

## CQ_1.1
Return the ID of the `discipline_a`.

```
PREFIX gtvo: <https://gotriple.eu/ontology/triple/gtvo#>
PREFIX datacite: <http://purl.org/spar/datacite/>

SELECT ?id WHERE {
  ?terms datacite:hasIdentifier ?id .
}
```

## CQ_1.2
Return all the ids of the terms/concepts inside the `discipline vocabulary`.

```
PREFIX skos: <http://www.w3.org/2004/02/skos/core#>
PREFIX gtvo: <https://gotriple.eu/ontology/triple/gtvo#>
PREFIX datacite: <http://purl.org/spar/datacite/>

SELECT ?ids WHERE {
  ?terms skos:inScheme gtvo:disciplines .
  ?terms datacite:hasIdentifier ?ids
}
```
