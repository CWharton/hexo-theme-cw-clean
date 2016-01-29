# Hexo CW-Clean
A clean light theme for [Hexo].

Live Example: [CWharton Blog](http://blog.cwharton.com)

## Install
Execute the following command and modify `theme` in `_config.yml` to `light`.

```bash
git clone https://github.com/hexojs/hexo-theme-cw-clean.git themes/cw-clean
```

## Enable
Go to the root directory of the blog and edit `_config.yml` so that `theme` is set to `cw-clean`.

## Update
Execute the following command to update Light.

```bash
cd themes/cw-clean
git pull
```

## Config
Edit `themes/cw-clean/_config.yml` for theme-specific configuration.

```yaml
menu:
   Home: /
   Archives: /archives

widgets:
- category
- tag

favicon: favicon.ico
google_analytics:
rss: /atom.xml

social_links: # for more icons, please see http://fontawesome.io/icons/#brand
   #<ICON>: <LINK>
   twitter: https://twitter.com/username
   github: https://github.com/username
   rss: /atom.xml

social_share:
   enable: true
   facebook: true
   facebook_appID: 11111111
   twitter: true
   twitter_username: username
   google: false
   pinterest: true

excerpt_link: Read More
fancybox: true
disqus_shortname: site name
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **favicon** - Site Icon
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link
- **social_links** - Links to blog social media. please see http://fontawesome.io/icons/#brand for more icons
- **social_share** - Share links in posts (some require IDs in order to work)
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles button
- **fancybox** - Enable [Fancybox]
- **disqus_shortname** - Disqus shortname **provided by Disqus
