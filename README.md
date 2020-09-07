# Awesome Identity

[![Netlify Status](https://api.netlify.com/api/v1/badges/43d34b47-3dee-43bb-a905-c7829ce5352b/deploy-status)](https://app.netlify.com/sites/awesome-identity/deploys)
[![CircleCI](https://circleci.com/gh/posquit0/hugo-awesome-identity.svg?style=shield)](https://circleci.com/gh/posquit0/hugo-awesome-identity)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

**Awesome Identity** is a single-page Hugo theme to introduce yourself. Add a portrait, an introduction, serveral links, and you're set.

![Awesome Identity Screenshot](https://raw.githubusercontent.com/posquit0/hugo-awesome-identity/master/images/screenshot.png)


## Features

* Extremely simple to use
* Responsive layout, supports any screen size
* Customizable theme colors
* Supports [Google Analytics](https://marketingplatform.google.com/about/analytics/)
* Live chat with [Crisp](https://crisp.chat/) integration


## Getting Started

To use this theme you will need to have Hugo installed. If you don't have Hugo installed please follow [Install Hugo](https://gohugo.io/getting-started/installing/).

### Create a new Hugo site

```bash
$ hugo new site my-identity
```

### Install the theme

If your site is under version control using git, the easiest way to install this theme is to add it as a submodule. Inside the directory of your Hugo site, run the following command.

```bash
$ git submodule add https://github.com/posquit0/hugo-awesome-identity themes/awesome-identity
```

Alternatively, you can clone the theme into your project.

```bash
$ git clone https://github.com/posquit0/hugo-awesome-identity themes/awesome-identity
```

### Configure Hugo

Add the following line to `config.toml` to tell Hugo to use the theme.

```toml
theme = "awesome-identity"
```

Alternatively, you can tell Hugo to use the theme with the `-t` option.

```bash
$ hugo server -t awesome-identity
```

### Run server for development

After installing the theme for the first time, generate the Hugo site.

```bash
$ hugo server
```

Now enter [localhost:1313](http://localhost:1313) in the address bar of your browser.


## Configuration

Take a look in the `exampleSite/` directory.

This directory contains an example config file and the content for the demo. It serves as an example setup for your documentation.

Copy the `config.toml` into the root directory of your website. Overwrite the existing config if necessary.

### Contacts

You can put your own contacts such as e-mail address, or social media accounts. The contacts will be linked using icons from [Font Awesome](https://fontawesome.com/).

Currently, Awesome Identity supports: Email, GitHub, Twitter, Facebook, LinkedIn, Instagram, StackOverflow, Keybase, and Medium. Feel free to [create Pull Request](https://github.com/posquit0/hugo-awesome-identity/pulls) if you need other contact type.

```toml
## Contacts Configurations
[params.contacts]
  email = "john.smith@example.com"
  github = "john.smith"
  gitlab = "john.smith"
  twitter = "john.smith"
  facebook = "john.smith"
  linkedin = "john.smith"
  instagram = "john.smith"
  stackoverflow = "7919458"
  keybase = "john.smith"
  medium = "john.smith"
  xing = "john.smith"
```

### Footer

```toml
## Footer Configurations
[params.footer]
  copyright = "© 2019 John Smith. [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)."
  poweredBy = true
```

### HTTP meta tags & OpenGraph

### Google Analytics

### Crisp

### Colors

### Internationalization (i18n)


## Update

If you have installed the theme as a git submodule, you can update the theme by issuing the following command inside your project directory.

```bash
$ git submodule update --remote --rebase
```

If you have cloned the theme, you can run `git pull` inside the theme directory.


## Contributing

This project follows the [**Contributor Covenant**](http://contributor-covenant.org/version/1/4/) Code of Conduct.

#### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/posquit0/hugo-awesome-identity/issues) to report any bugs or ask feature requests.


## License

Provided under the terms of the [MIT License](https://github.com/posquit0/hugo-awesome-identity/blob/master/LICENSE).

Copyright © 2019-2020, [Byungjin Park](http://www.posquit0.com).


## See Also

* [Awesome CV](https://github.com/posquit0/Awesome-CV) - LaTeX template for your outstanding job application.
