# pronami_php

Study PHP by below book.

- 気づけばプロ並みPHP 改訂版--ゼロから作れる人になる!
  - http://amazon.jp/dp/4865940650

# Dependencies
Managed by composer

```bash
$ docker-compose run --rm php-cli composer show
```

# DB Migration
Manged by phinx

- http://docs.phinx.org/en/latest/index.html

```bash
# Create
$ vendor/bin/phinx create CreateProductTable
# Migrate
$ vendor/bin/phinx migrate
# Rollback
$ vendor/bin/phinx rollback
```
# 参照
- https://github.com/budougumi0617/pronami_php

# 起動
- `docker-compose up`
- `docker-compose down`