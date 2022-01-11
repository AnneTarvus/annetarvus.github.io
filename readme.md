# Annen kotisivut

1. Jos terminaali ei auki, paina Ctrl - ö
2. Kirjoita komento `jekyll serve --config .\_devconfig.yml`
3. Pitäisi sanoa Server running... ja sivu pyörii localhost:4000
4. Muokkaa haluamaa .md tiedostoa ja tarkista muutokset lokaalista versiosta
5. Kun olet valmis, mene terminaaloiin ja paina Ctrl - c, ja varmista Y
6. Kirjoita komento `git add *` lisätäksesi muutokset versionhallintaan
7. Kirjoita komento `git commit -m "Viesti mitä muutettu"`
8. Kirjoita komento `git push` viedäksesi commitatut muutokset liveen

## Markdown ohjeet
### Otsikot
```markdown
# Iso otsikko
## Keskikokoinen otsikko
### Pieni otsikko
```
### Listat
* asia
* toinen

1. numeroitu
2. toinen
### Linkit
[Teksti](www.linkki.com)
### Tekstiefektit
**Lihavointi**
*Kursivointi*
~~Yliviivaus~~
