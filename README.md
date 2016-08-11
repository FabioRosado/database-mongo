# opsdroid database mongo

A database module for [opsdroid](https://github.com/opsdroid/opsdroid) to persist memory in a [mongo database](https://www.mongodb.com/).

## Requirements

None.

## Configuration

```yaml
databases:
  mongo:
    host:       "my host"     # (optional) default "localhost"
    port:       "12345"       # (optional) default "27017"
    database:   "mydatabase"  # (optional) default "opsdroid"
```

## License

GNU General Public License Version 3 (GPLv3)
