Inspirado em: https://just-the-docs.github.io/just-the-docs/

Instalação de pacotes:

    sudo apt-get install libxml2-dev libxslt-dev build-essential libxml2 libxml2-dev libxslt1-dev ruby-dev ruby-bundler nodejs
    sudo gem install bundler
    sudo gem install bundler:2.3.26

Subindo ambiente dev:

    git clone git@github.com:VOCE/fflch.github.io.git
    cd fflch.github.io
    bundle config set --local path 'vendor/bundle'
    bundle _2.3.26_ install
    bundle exec jekyll serve

