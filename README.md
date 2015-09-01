jekyll-nginx
===============

A base container to serve Jekyll content using Nginx. Saves memory and deploy time.

You don't need to use Jekyll to serve your site - you can just compile the files and use anything - `jekyll build`

This is a container that has Ruby, Python 2.7 and Jekyll available, to compile and build the static site, that nginx serves.

You can use our container: `docker pull platanus/jekyll-nginx`

Or you can build your own:

```
docker build -t your-name-here/jekyll-nginx .
docker push your-name-here/jekyll-nginx
```

Push it to your docker server - and your server will use 4-6MB of RAM instead of 50MB.

To see an example working repo, [take a look here](https://github.com/platanus/blog).
