# How to generate theme.pot file
```
  find . -iname "*.html" -or -iname "*.txt" -or -iname "*.underscore" | xargs xgettext -L Python --from-code=UTF-8 -o translations/theme.pot
```