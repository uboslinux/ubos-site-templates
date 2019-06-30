# Templates for common site configurations

If you have a physical or virtual computer running UBOS (see
[UBOS quickstart](https://ubos.net/quickstart/), you can quickly set
up a website with a variety of functionality using one of the following
site templates.

Simply copy the URL to one of the site templates below, and, once logged
into your UBOS device as ``shepherd``, execute:

```
sudo ubos-admin createsite --from-template <url>
```
where `<url>` is the URL you copy-pasted from below.

Example:

```
sudo ubos-admin createsite --from-template https://github.com/uboslinux/ubos-site-templates/...
```

## Simple WordPress site

Provides basic blogging functionality.

| Without encryption                                                     | With Letsencrypt encryption                           |
|------------------------------------------------------------------------|-------------------------------------------------------|
| [wordpress.json](https://github.com/uboslinux/ubos-site-templates/...) | https://github.com/uboslinux/ubos-site-templates/...) |

## WordPress site with IndieWeb plugins



## Simple Known ("IndieWeb") site


## Nextcloud site with common apps


## Personal website with IndieWeb WordPress blog on the front page, and Nextcloud for file sharing and collaboration


## Personal website with Known blog on the front page, and Nextcloud for file sharing and collaboration


