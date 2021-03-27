# Backa Boulder Website

Source code for Backa Boulder website. This is a static site that is generated using [Hugo](https://gohugo.io).


## Directoy structure

```
├── assets
│   └── css - css files
├── content
│   ├── en - English content pages
│   └── se - Swedish content pages
├── data - Data files (opening hours, prices and contact info)
├── i18n - Some translations of things that don't live in the content folder
├── layouts - HTML layouts
└── static
    └── images - Images
```


## Deploy

Changes will be deployed on merge to main branch by cloudflare pages.


## Local Development

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo).
2. Checkout this repo locally.
3. Open a terminal in the folder where the project lives.
4. Run `hugo server` (outout of this commend shows where you can view the site).
5. Make changes and view them locally until happy.
6. Commit, push changes, open merge request and merge to deploy.
