Yarn Website
[![Netlify Status](https://api.netlify.com/api/v1/badges/85057564-01fa-49d4-b898-30acb74ae19e/deploy-status)](https://app.netlify.com/sites/yarnpkg/deploys)
============

Это репозиторий содержит исходный код сайта Yarn Classic (v1), доступного по адресу https://classic.yarnpkg.com/. 
Для сайта Yarn v2 см. https://github.com/yarnpkg/berry/tree/master/packages/gatsby

[README in Japanese](README.ja.md)

Для того чтобы приступить к работе:

```sh
$ git clone git@github.com:yarnpkg/website.git yarn-website
$ cd yarn-website
```

Вы должны убедиться, что у вас установлены Yarn и [Bundler](http://bundler.io/):

```sh
$ gem install bundler
```

А потом:

```sh
$ make
```

Или:

```sh
$ make install
$ make serve
```

В Windows `make` недоступен, поэтому вам нужно выполнить `bundle` и `jekyll` напрямую:

```sh
bundle install
bundle exec jekyll serve --incremental
```

---

**Особая благодарность компании [Netlify](https://www.netlify.com/) за обеспечение работы сайта.**
