---
layout: page
title: Data 101 Assignment Tips
nav_exclude: true
description: >-
    PostgreSQL meta-commands and jupysql
markdown: kramdown
---

# {{page.title}}
{:.no_toc}
Author: Lisa Yan
Last updated: August 27, 2023 (Fall 2023)

Jump to:
* TOC
{:toc}

<br>

Overview things

Strongly encourage students to look at postgres documentation

* `jupysql`
* `psql` PostgreSQL client

Citation and collaboration: See syllabus.

## DataHub

### Working with Jupyter Notebooks

Reference Data 100 documentation

Uses otter grader, custom python packages, and a PostgreSQL server, so we recommend you always work on DataHub. While you are welcome to set up everything locally, when grading we will assume that your submission was developed on DataHub. Staff will not be able to debug/support local setup issues.

**Scratchwork**: If you would like to add new cells, always do so **before** the cell in which you end up writing your answer. Failure to do so may break the auto-grader.

### DataHub's local PostgreSQL Server

Instead of connecting to a remote server, we actually connect to a local server

`joyvan` - what does it mean? GitHub issues on [Jupyter](https://github.com/jupyter/docker-stacks/issues/358), [JupyterHub](https://github.com/jupyterhub/repo2docker/issues/366)


## PostgreSQL via Python package `jupysql`

package and cell magic

How to use `%sql` and `%%sql`

Launch client conection

## PostgreSQL Client CLI

CLI: Command-Line Interface

### Launching postgres client via `psql`

`cd` into the directory

```
psql -h localhost -d imdb -f data/imdbdb.sql
psql postgresql://jovyan@127.0.0.1:5432/postgres
```

ctrl-C to cancel

### meta-commands

postgres meta-commands doc: [list](https://www.postgresql.org/docs/15/app-psql.html)

* `\d` relations
* `\l` databases



* `\c postgresql://jovyan@127.0.0.1:5432/imdb` to close connection to current database and switch to `imdb1 located on that server

### Making queries via CLI

* Need to end with semicolon
* Sometimes launches another display screen. If you see `(END)`, then you press `<space>` to display more, or `q` to quit.

* Caution about multiple connections

## PostgreSQL details

### Catalog, Schema, Relation/Table, etc.

* StackOverflow: [Catalog, Schema, Relation/Table differences](https://stackoverflow.com/questions/7022755/whats-the-difference-between-a-catalog-and-a-schema-in-a-relational-database)

* `pg_toast`: TOAST storage schema [documentation 73.2](https://www.postgresql.org/docs/current/storage-toast.html)
* `pg_catalog`: System catalog schema [documentation 5.9.5](https://www.postgresql.org/docs/current/ddl-schemas.html#DDL-SCHEMAS-CATALOG)

## Debugging on DataHub

ruined database? Just relaunch your DataHub server

will need to reload in default database, if does not exist
