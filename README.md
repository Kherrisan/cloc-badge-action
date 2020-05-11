# cloc-badge-action
cloc-badge-action

Generating badge for line of codes with Github action.

![](https://raw.githubusercontent.com/Kherrisan/cloc-badge-action/master/cloc.svg)

## How to

1. Add the action to your repository workflows.
2. Each time the workflows is running, it will generating a new badge svg file in the root directory, then commit and push to your repo.
3. Link the svg in your .md or .html using syntax like:

```
![](https://raw.githubusercontent.com/Kherrisan/cloc-badge-action/master/cloc.svg)
```

[Demo workflow file](https://github.com/Kherrisan/cloc-badge-action/blob/master/.github/workflows/blank.yml)