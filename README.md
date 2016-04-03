# my-atom-packages
A list of my favorite atom packages:

- atom-beautify
- atom-ternjs
- autoclose-html
- color-picker
- css-comb
- editor-stats
- goto
- highlight-line
- highlight-selected
- js-hyperclick
- language-babel
- linter
- linter-eslint
- merge-conflicts
- minimap
- minimap-highlight-selected
- monokai-seti
- pigments
- react
- react-snippets
- seti-ui

## Install packages
To install these packages, run:
```
apm install atom-beautify atom-ternjs autoclose-html color-picker css-comb editor-stats goto highlight-line highlight-selected js-hyperclick language-babel linter linter-eslint merge-conflicts minimap minimap-highlight-selected monokai-seti pigments react react-snippets seti-ui
```

## Get your installed packages

To get the installed packages, run:
```
apm list | grep "/home/simon" -A 25 | grep -v "/home/simon" | awk '{sub(/@.*/,""); print}' | awk '{sub(/.* /,""); print}'
```

To get the installed packages with space instead of new line, run:
```
apm list | grep "/home/simon" -A 25 | grep -v "/home/simon" | awk '{sub(/@.*/,""); print}' | awk '{sub(/.* /,""); print}' | sed '{:q;N;s/\n/ /g;t q}'
```
