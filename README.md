# examples

## Hello World

### module.json

```json
{
    "module": "i5.examples.hello_world",
    "import": {
        "std": "salifm.i5l.std"
    }
}
```

### main.i5

```i5
proc main() {
    std->println("Hello World!")
}
```
