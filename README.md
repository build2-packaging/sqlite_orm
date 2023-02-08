# SQLite ORM Build2 Package

[![build2](https://github.com/build2-packaging/sqlite_orm/actions/workflows/build2.yml/badge.svg)](https://github.com/build2-packaging/sqlite_orm/actions/workflows/build2.yml)

This project builds and defines the build2 package for the [SQLite ORM](https://sqliteorm.com/) library.

The packaging code is licensed under the MIT License, the upstream artifacts are licensed under the terms and conditions of SQLite ORM.

## Usage

You can simply add this package as dependency to your project by specifying it in your `manifest`:

```
depends: libsqlite_orm ^1.0.0
```

Then just pick the targets that you need:

```
import libs  = libsqlite_orm%lib{sqlite_orm}
```
