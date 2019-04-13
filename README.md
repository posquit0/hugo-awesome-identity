# Awesome Identity Theme for Hugo


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

Add these parameters to your `config.toml`:

```toml
[params]
```


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

Copyright © 2019, [Byungjin Park](http://www.posquit0.com).
