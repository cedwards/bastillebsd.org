# bastillebsd.org
Bastille Template: bastillebsd.org website

Usage:

```shell
bastille bootstrap https://github.com/cedwards/bastillebsd.org
bastille template TARGET cedwards/bastillebsd.org
```

## Template Overview

```shell
Template: https://github.com/cedwards/bastillebsd.org

Already up to date.

Detected PKG hook.
[PKG]:
nginx-lite

Detected SYSRC hook.
[SYSRC]:
nginx_enable=YES

Detected CMD hook.
[CMD]:
nginx -t && service nginx restart

Detected CONFIG hook.
[usr]:
/usr/local/bastille/templates/cedwards/bastillebsd.org/usr
└── local
    ├── etc
    │   └── nginx
    │       ├── nginx.conf
    │       └── sites.d
    │           └── bastillebsd.org.conf
    └── www
        └── bastillebsd.org
            └── html
                ├── 404.html
                ├── categories
                │   ├── index.html
                │   ├── index.xml
                │   └── page
                │       └── 1
                │           └── index.html
                ├── home
                │   └── index.xml
                ├── img
                │   ├── .DS_Store
                │   ├── icon-192.png
                │   ├── icon-32.png
                │   ├── icon.png
                │   └── portrait.jpg
                ├── index.html
                ├── index.json
                ├── index.xml
                ├── js
                │   ├── academic-bundle-pre.min.js
                │   ├── academic.min.14cafafda844d960749b7551524d1c3a.js
                │   └── vendor
                │       └── reveal.js
                │           └── plugin
                │               └── notes
                │                   ├── notes.html
                │                   └── notes.js
                ├── post
                │   ├── index.html
                │   ├── index.xml
                │   └── page
                │       └── 1
                │           └── index.html
                ├── publication
                │   ├── index.html
                │   └── index.xml
                ├── publication_types
                │   ├── index.html
                │   ├── index.xml
                │   └── page
                │       └── 1
                │           └── index.html
                ├── site.webmanifest
                ├── sitemap.xml
                ├── styles.css
                ├── tags
                │   ├── index.html
                │   ├── index.xml
                │   └── page
                │       └── 1
                │           └── index.html
                └── talk
                    ├── index.html
                    └── index.xml

28 directories, 35 files

Template ready to use.
```
