## Stacker

Things get way more complicated for developers when it comes to pushing their apps live to the web.

Stacker makes configuring web servers a cinch, letting developers focus on what they're good at.

You can install the following stack with the help of Stacker build:

- Languages
  - PHP (7.2)
  - PHP-FPM (7.2)
  - Python (3.6)
  - Nodejs (6.1) (coming soon)
- Databases (coming soon)
  - MySQL
  - PostgreSQL
  - MongoDB
  - Redis
  - Memcached
- Web Servers
  - NGINX
  - Apache (coming soon)
- SSL
  - Letsencrypt
  - Webroot
  - Certbot (coming soon)
- Tools
  - Git
  - cURL
  - wget
  - Unzip
- And more..

### Installation

```curl
curl -sSL https://raw.githubusercontent.com/mystroken/stacker/master/install.sh | bash
```

### Build

Once installed, simply run the below command to install the latest stack of your choice.

```curl
stacker build
```

### Usage

In order to map a new site, say example.com (or) ex.example.com, over **HTTP** or **HTTPS**, use the below command.

```curl
stacker site
```

Simply follow the prompts to seamlessly map your domains/sub-domains to your application with optional free SSL certificate installation.

> Note: Make sure to provide the publicly serving folder to serve the application.

You can check the SSL strength at [SSL Labs](https://www.ssllabs.com/ssltest/), which ideally analyses and show **A+** rating.

## Contributing

The idea is to build and improve this package to support other language builds as well.
If you have any contributions on how to expand this package, don't hesitate to fork and make pull requests.

I'm no expert and I strongly sense that there are many ways to improve the existing ideas.
Any [open issues](https://github.com/santoshbaggam/stacker/issues) can be discussed and solved together! :)

## License

Stacker is released under the [MIT License](https://github.com/santoshbaggam/stacker/blob/master/LICENSE).
