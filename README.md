# CSQLite

System SQLite module for Swift.

## Linux:

sudo apt-get install libsqlite3-dev

## OS X:

Build sqlite3 from source and install it into the same path as the Linux version.

```
cd sqlite-autoconf-3120200
configure --prefix=/usr/local
make install
```

In your project, make sure to point linker to the correct sqlite version:
```
swift build -Xlinker -L/usr/local/lib
```

If you're looking for SQLite wrapper for Swift 3.0 + SPM (Swift Package Manager), check this repository:
https://github.com/zmeyc/SQLite.swift
