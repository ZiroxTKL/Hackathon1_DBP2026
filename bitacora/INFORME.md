| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | Historial de commits borrados | diff-filter | git show f1cff3f~1:bitacora/frag-01.txt > bitacora/frag-01.txt | f1cff3f~1 |
| FRAG-02 | Tag anotado en la cinta | cat-file tag | git cat-file -p respaldo/pre-incidente | respaldo/pre-incidente |
| Glifo del sello | Tag anotado en la cinta | show desde tag | git show respaldo/pre-incidente:assets/sello.svg > assets/sello.svg | respaldo/pre-incidente |