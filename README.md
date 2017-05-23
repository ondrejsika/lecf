# lecf

    Ondrej Sika <ondrej@ondrejsika.com>

__Let's Encrypt with Cloudflare__

This repo is compose of:

- https://github.com/lukas2511/dehydrated
- https://github.com/kappataumu/letsencrypt-cloudflare-hook

Thank you guys!


## Usage

Create config:

    echo export CF_EMAIL=email > config
    export CF_KEY=key >> config

Create cert:

    ./run <domain>

Cretificate are:

    certs/<domain>/

