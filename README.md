<p align="center">
    <img src="/src/favicon.jpg" alt="Logo" width="450">
</p>

Pharos resource center built with a starter documentation theme for [Gridsome](https://gridsome.org/).

## Installation

Ensure you have Gridsome installed...see here [Gridsome How To Install](https://gridsome.org/docs/#how-to-install)

Once you have the Gridsome CLI installed, simply run:

`gridsome create your-project https://github.com/randrewsimcdi/docc`

## Documentation

Documentation can be found [here](https://docc-theme.netlify.com/).

## Managing Content 

Currently, using [Netlify CMS] (https://www.netlifycms.org/)

Log in by getting access to the GitHub repo then going to OurDomainName.com/admin 

Publishing a documentation article requires the following fields...see below as reference 

```
title: "Creating Users"
description: "Pharos CRM: Creating Users"
url: crm-creating-users
sidebar: docs
date: 2020-09-24T12:10:53.448Z
```

Optional fields to have next page or prev page buttons

```
next: /docs/next-doc
prev: /docs/prev-doc
```

Note: the sidebar field must contain `docs`


## Publishing Content 

Once you click publish, the article gets pushed to Github, then deployed automatically by Netlify. 

## Add to Menu Bar

Edit the file `gridsome.config.js` 
Add your article url to the items 
Save file and commit to Github with the messsage `menu update: article name, article name, article name`
Wait 1-3 minutes for site to be live

```js
// gridsome.config.js
module.exports = {
  // ...
  settings: {
    sidebar: [
      name: 'docs',
      sections: [
        {
          title: 'Getting Started',
          items: [
            '/docs/',
            '/docs/installation/',
            '/docs/writing-content/',
          ]
        },
      ]
    ]
  },
  // ...
}
```