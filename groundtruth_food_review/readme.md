# Mapping (YARRRML to RML to RDF)
## Ingredients
```bash
yarrrml-parser -i ingredients.yarrrml.yml -o ingredients.rml.ttl
java -jar ../_rmlmapper.jar -m ingredients.rml.ttl -o ingredients.ttl -s turtle
```
➡️ ingredients.ttl