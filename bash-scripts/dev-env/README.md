# Unix Tools

## JQ

### Install

```bash
sudo apt-get install jq
```

### Lets create a file with the following content

```json
{"type": "foo", "values": [1, 2, 3, 4, 5]}
{"type": "foo", "values": [69, 420, 42, 69420]}
{"type": "bar", "values": {"a": 42, "b": 69}}
{"type": "bar", "values": {"a": 1337, "b": 420}}
{"type": "bar", "values": {"a": 111, "b": 222}}
```

### Prettify logs

```bash
cat file.json | jq
```

### Compact json

```bash
cat file.json | jq -c
```