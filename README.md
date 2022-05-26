# Broken links


The files [en.csv](./en.csv) and [ru.csv](./ru.csv) contain tables of broken links which I got via
```sh
linkinator -r --format=csv --concurrency=400 --verbosity=error https://developer.mozilla.org/en/docs/Web |& tee -a en.csv
```

For this task, I installed [linkinator](https://github.com/JustinBeckwith/linkinator#installation)

Please suggest how at least some of these broken links can be efficiently updated on the website.
