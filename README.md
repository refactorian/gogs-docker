<p align="center"><img src="https://gogs.io/img/hero.png" width="500"></p>

# Gogs Docker
- Gogs v0.13.x
- Postgres v16.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy
- `docker compose up -d`

# Notes

### Gogs App
- URL: http://localhost:3000

### Docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`

# What is Gogs?

Gogs is a painless self-hosted Git service.

## Vision

This project aims to build a simple, stable and extensible self-hosted Git service that can be setup in the most painless way. With Go, this can be done with an independent binary distribution across ALL platforms that Go supports, including Linux, macOS, Windows and ARM.

## Open Source Components

- Web Framework: [Macaron](http://go-macaron.com)
- UI Components:
    - [Semantic UI](http://semantic-ui.com/)
    - [GitHub Octicons](https://octicons.github.com/)
    - [Font Awesome](http://fontawesome.io/)
- Front-end Plugins:
    - [DropzoneJS](http://www.dropzonejs.com/)
    - [highlight.js](https://highlightjs.org/)
    - [clipboard.js](https://zenorocha.github.io/clipboard.js/)
    - [emojify.js](https://github.com/Ranks/emojify.js)
    - [jQuery Date Time Picker](https://github.com/xdan/datetimepicker)
    - [jQuery MiniColors](https://github.com/claviska/jquery-minicolors)
    - [CodeMirror](https://codemirror.net/)
    - [notebook.js](https://github.com/jsvine/notebookjs)
    - [marked](https://github.com/chjj/marked)
- ORM: [Xorm](https://github.com/go-xorm/xorm)
- Database Drivers:
    - [github.com/go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)
    - [github.com/lib/pq](https://github.com/lib/pq)
    - [github.com/mattn/go-sqlite3](https://github.com/mattn/go-sqlite3)
    - [github.com/denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb)
- And all other Go package dependencies