# TERN Organisations and Persons Ontology

Documentation online: https://ternaustralia.github.io/ontology_tern-org/


## Building the documentation

In the directory of /docs, run:

```
docker run --rm -it --name pylode -e ONTOLOGY_FILE=tern-org.ttl -e OPTIONS="--css true" -v ${PWD}:/pyLODE/src/pylode/input edmondchuc/pylode
```