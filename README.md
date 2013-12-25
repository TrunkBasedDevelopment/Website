The blog content is on the [gh-pages branch](https://github.com/paul-hammant/tbd/tree/gh-pages)

The third branch (you're looking at 'master' now) was pulled from the theme "So Simple".  Their 'master' (as per their forking instructions) is mapped to our 'so-simple-theme-master' branch:

```
git remote add so-simple-theme-origin https://github.com/mmistakes/so-simple-theme.git
git fetch so-simple-theme-origin master:so-simple-theme-master
```

Yes it's ironic, we're using multiple branches concurrently for a site that promotes Trunk Based Development.