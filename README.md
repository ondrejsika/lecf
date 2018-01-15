# lecf

    Ondrej Sika <ondrej@ondrejsika.com>

__Let's Encrypt with Cloudflare__

This repo is compose of:

- https://github.com/lukas2511/dehydrated
- https://github.com/kappataumu/letsencrypt-cloudflare-hook

Thank you guys!


## Install

    git clone git@github.com:ondrejsika/lecf.git
    cd lecf

For Python 3

    pip install hooks/cloudflare/requirements.txt

For Python 2

    pip install hooks/cloudflare/requirements-python-2.txt


## Usage

Create config:

    echo export CF_EMAIL=email > config
    echo export CF_KEY=key >> config

Create cert:

    ./run <domain>

Cretificate are:

    certs/<domain>/

