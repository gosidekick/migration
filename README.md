# migration
[![Build Status](https://travis-ci.com/gosidekick/migration.svg?branch=master)](https://travis-ci.com/gosidekick/migration)
[![Go Report Card](https://goreportcard.com/badge/github.com/gosidekick/migration/v2)](https://goreportcard.com/report/github.com/gosidekick/migration/v2)
[![GoDoc](https://godoc.org/github.com/gosidekick/migration/v2?status.png)](https://godoc.org/github.com/gosidekick/migration/v2)
[![MIT Licensed](https://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)
[![codecov](https://codecov.io/gh/gosidekick/migration/branch/master/graph/badge.svg)](https://codecov.io/gh/gosidekick/migration)

PostgreSQL migration tool with transactions

```console
./migration -url "postgres://postgres@localhost:5432/dbname?sslmode=disable" -dir ./fixtures -action up
```

```console
./migration exec -url "postgres://postgres@localhost:5432/dbname?sslmode=disable" -dir ./fixtures -action down 2
```

```console
./migration exec -url "postgres://postgres@localhost:5432/dbname?sslmode=disable" -dir ./fixtures -action status
```