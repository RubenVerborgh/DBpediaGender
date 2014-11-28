# DBpedia Gender Extraction

Tools for extracting gender information into [DBpedia](http://dbpedia.org/).

## list-people
Creates a list of people from the given [triple pattern fragments](http://linkeddatafragments.org/in-depth/#tpf) source.

```
$ ./list-people http://fragments.dbpedia.org/2014/nl > people_nl.ttl
```

## determine-gender
Extracts gender information for the given list of people.

```
$ ./determine-gender people_nl.ttl
```
