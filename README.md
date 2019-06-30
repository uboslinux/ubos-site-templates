<a href="https://ubos.net/"><img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/ubos-160x160.png"></a>

# Templates for common website configurations

If you have a physical or virtual computer running [UBOS](https://ubos.net/)
(see [UBOS quickstart](https://ubos.net/quickstart/)), you can quickly set
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
sudo ubos-admin createsite --from-template https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress.json
```

Note: Currently requires UBOS on the development branch. Will be available in
production in the future.

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/wordpress-144x144.png">

## Simple WordPress site

Provides basic blogging functionality.

| Without encryption                                                                            | With Letsencrypt encryption                                                                                           |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [wordpress.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress.json) | [wordpress-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress-letsencrypt.json) |

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/wordpress-144x144.png">

## WordPress site with IndieWeb plugins

Interact with the social web from your own WordPress site, using the [IndieWeb](https://indieweb.org/).

| Without encryption                                                                                              | With Letsencrypt encryption                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| [wordpress-indieweb.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress-indieweb.json) | [wordpress-indieweb-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress-indieweb-letsencrypt.json) |

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/known-144x144.png">

## Simple Known ("native IndieWeb") site

Interact with the social web from your own website, using the [IndieWeb](https://indieweb.org/).

| Without encryption                                                                    | With Letsencrypt encryption                                                                                   |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| [known.json](https://github.com/uboslinux/ubos-site-templates/blob/master/known.json) | [known-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/known-letsencrypt.json) |

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/nextcloud-144x144.png">

## Nextcloud site with common apps

File sync and share for your own devices, and with others. Also calendaring, contacts and more.

| Without encryption                                                                            | With Letsencrypt encryption                                                                                           |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [nextcloud.json](https://github.com/uboslinux/ubos-site-templates/blob/master/nextcloud.json) | [nextcloud-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/nextcloud-letsencrypt.json) |

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/wordpress-144x144.png">
<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/nextcloud-144x144.png">

## Personal website with IndieWeb WordPress blog, and Nextcloud for file sharing and collaboration

| Without encryption                                                                                                                  | With Letsencrypt encryption                                                                                                                                 |
|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [wordpress-indieweb-nextcloud.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress-indieweb-nextcloud.json) | [wordpress-indieweb-nextcloud-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/wordpress-indieweb-nextcloud-letsencrypt.json) |

<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/known-144x144.png">
<img align="right" src="https://raw.githubusercontent.com/uboslinux/ubos-site-templates/master/assets/nextcloud-144x144.png">

## Personal website with Known blog, and Nextcloud for file sharing and collaboration

| Without encryption                                                                                        | With Letsencrypt encryption                                                                                                       |
|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| [known-nextcloud.json](https://github.com/uboslinux/ubos-site-templates/blob/master/known-nextcloud.json) | [known-nextcloud-letsencrypt.json](https://github.com/uboslinux/ubos-site-templates/blob/master/known-nextcloud-letsencrypt.json) |

## Questions?

Post to the [forum](https://forum.ubos.net/).
