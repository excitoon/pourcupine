# Pourcupine

Tool for keeping git forks in sync.

## Usage

```
pourcupine
```

## `.pourcupinerc` format

```
{
    "repositories": {
        "<DST>": {
            "source": "<SRC>"
        },
        ...
        "<DST>": {
            "source": "<SRC>"
        }
    }
}
```

## Dependencies

- Python 3
- Git
