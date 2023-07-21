# Notes

## Publish HTML and PDF

```sh
asciidoctor -R source -D site source/index.adoc source/links.adoc
asciidoctor -R source -D site source/*.adoc
git add .
git commit -m "change index and links"
git push
```

```sh
asciidoctor-pdf -D pdf source/links.adoc
```
