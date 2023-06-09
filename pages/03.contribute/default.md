---
title: Contribute
body_classes: 'title-center title-h1h2'
allowCSS: default
allowJS: default
show_header_image: false
show_clickthrough: true
---

If you'd like to contribute, you may do so by obtaining a Github account, forking and then sending pull requests with your work. The structure in creating posts and pages is the same as Grav itself, except you may use your favorite text editor. I use a mixture of the Grav admin UI, Visual Studio Code and nano (yes, nano).

## Creating a blog post

The shared "posts" directory goes as such:

```
pages/
├── 01.home
│   └── default.md
├── 02.blog
│   ├── argus-ii-retinal-implant
│   │   └── item.md
│   ├── blog.md
│   ├── elon-musk-bbc-interview
│   │   └── item.md
│   ├── jabber-who
│   │   └── item.md
│   ├── search-engines-and-ai
│   │   └── item.md
│   └── stay-local
│       └── item.md
└── misc
    ├── blog.md
    └── test
        └── item.md
```

Under /blog you have many sub directories with their own item.md. You would create a new directory with "title-here" followed by an item.md. In the item.md we would have:

```context
---
title: 'Stay local'
publish_date: '26-03-2023 14:13'
allowCSS: default
allowJS: default
show_header_image: false
show_clickthrough: true
taxonomy:
    category:
        - Local
    tag:
        - local
        - openhab
        - privacy
        - data
---
```

Below the second "---" you would begin your article. The entire .md would read:

```context
---
title: 'Stay local'
publish_date: '26-03-2023 14:13'
allowCSS: default
allowJS: default
show_header_image: false
show_clickthrough: true
taxonomy:
    category:
        - Local
    tag:
        - local
        - openhab
        - privacy
        - data
---

While I welcome and encourage a transition to becoming more of a cyborg, I stress the importance of making sure data is kept local. Many times - without punishment - companies have failed to protect data or have outright sold data unbeknownst to customers. 

Projects such as OpenHAB are a true step forward.
```

In terms of editing style, Markdown is the choice.

GH: [https://github.com/snick512/grav](https://github.com/snick512/grav)

Email: snick512@pm.me

Twitter: [@snick512](https://twitter.com/snick512)

This could be a collective effort! Contact if interested. 😊