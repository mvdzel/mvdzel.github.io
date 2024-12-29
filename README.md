https://jekyllrb.com/docs/
https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll

Don't forget to comment out jekyll in _config.yml

> docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:pages sh
> bundle exec jekyll build
