```
echo "Тайӧ нигаыс сетас сӧмын ичӧтик юкӧн ывлавыв велӧдысьлы." \
| hfst-tokenize --giella-cg /Users/niko/langtech/main/langs/kpv/tools/tokenisers/tokeniser-disamb-gt-desc.pmhfst \
| vislcg3 -g /Users/niko/langtech/main/langs/kpv/src/syntax/disambiguation.cg3 | pbcopy

echo "" | kpvtoka
```

There is some problem in script output now.

- search: `(\t\")([а-яӧэі,.—]+)( )(.+)"`
- replace: `$1$2"$3$4`

- search: `[^\t]+(\t[^\t]+\t[^\t]+\t[^\t]+\t_$)`
- replace: `_$1`

```
pbpaste | python vislcg3-to-conllx-input.py
```