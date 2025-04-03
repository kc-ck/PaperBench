# CK Notes
See: 
- https://openai.com/index/paperbench/
- [Paper](https://cdn.openai.com/papers/22265bac-3191-44e5-b057-7aaacd8e90cd/paperbench.pdf)
- [Hacker News Discussion](https://news.ycombinator.com/item?id=43558858)
  

# Preparedness Evals

This repository contains the code for multiple Preparedness evals that use nanoeval and alcatraz.

## System requirements

1. Python 3.11 (3.12 is untested; 3.13 will break [chz](https://github.com/openai/chz))

## Install pre-requisites

```bash
for proj in nanoeval alcatraz nanoeval_alcatraz; do
    pip install -e project/"$proj"
done
```

## Evals

- [PaperBench](./project/paperbench/README.md)
- SWELancer (Forthcoming)
- MLE-bench (Forthcoming)
