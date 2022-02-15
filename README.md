
1. Edit [index.md](https://github.com/gt-bioss/hybrid22/edit/main/index.md)
2. Commit
3. Wait 1-2min

Local build:
```
docker run --rm --volume=$PWD:/srv/jekyll -it jekyll/jekyll jekyll build
```
