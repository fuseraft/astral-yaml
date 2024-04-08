# astral yaml

A YAML parser written in [Astral](https://github.com/fuseraft/astral).

### Usage

```
astral yaml <yaml_file>
```

### Example

```
astral yaml test.yml > test-tokens.txt
```

### Output

```
LITERAL:            `server`
COLON:              `:`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `host`
COLON:              `:`
LITERAL:            `localhost`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `port`
COLON:              `:`
NUMERIC_LITERAL:    `808`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `enabled`
COLON:              `:`
LITERAL:            `true`
LF:                 `\n`
LF:                 `\n`
LITERAL:            `database`
COLON:              `:`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `host`
COLON:              `:`
LITERAL:            `db.local`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `port`
COLON:              `:`
NUMERIC_LITERAL:    `543`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `username`
COLON:              `:`
LITERAL:            `admin`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `password`
COLON:              `:`
LITERAL:            `secret`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `settings`
COLON:              `:`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `connections`
COLON:              `:`
NUMERIC_LITERAL:    `1`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `timeout`
COLON:              `:`
NUMERIC_LITERAL:    `3`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `lazyLoad`
COLON:              `:`
LITERAL:            `true`
LF:                 `\n`
LF:                 `\n`
LITERAL:            `services`
COLON:              `:`
LF:                 `\n`
SPACE:              ` `
DASH:               `-`
SPACE:              ``
LITERAL:            `name`
COLON:              `:`
LITERAL:            `userservice`
LF:                 `\n`
SPACE:              `   `
LITERAL:            `url`
COLON:              `:`
LITERAL:            `http://localhost:8000/users`
LF:                 `\n`
SPACE:              `   `
LITERAL:            `methods`
COLON:              `:`
LF:                 `\n`
SPACE:              `     `
DASH:               `-`
SPACE:              ``
LITERAL:            `GET`
LF:                 `\n`
SPACE:              `     `
DASH:               `-`
SPACE:              ``
LITERAL:            `POST`
LF:                 `\n`
SPACE:              ` `
DASH:               `-`
SPACE:              ``
LITERAL:            `name`
COLON:              `:`
LITERAL:            `paymentservice`
LF:                 `\n`
SPACE:              `   `
LITERAL:            `url`
COLON:              `:`
LITERAL:            `http://localhost:8001/pay`
LF:                 `\n`
SPACE:              `   `
LITERAL:            `methods`
COLON:              `:`
LF:                 `\n`
SPACE:              `     `
DASH:               `-`
SPACE:              ``
LITERAL:            `POST`
LF:                 `\n`
LF:                 `\n`
LITERAL:            `logging`
COLON:              `:`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `level`
COLON:              `:`
LITERAL:            `debug`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `format`
COLON:              `:`
QUOTED:             `[%d{HH:mm:ss}] [%t] %-5level - %msg%n`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `destinations`
COLON:              `:`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `console`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `file`
LF:                 `\n`
SPACE:              `   `
DASH:               `-`
SPACE:              ``
LITERAL:            `syslog`
LF:                 `\n`
LF:                 `\n`
LITERAL:            `nested_structures`
COLON:              `:`
LF:                 `\n`
SPACE:              ` `
LITERAL:            `level1`
COLON:              `:`
LF:                 `\n`
SPACE:              `   `
LITERAL:            `level2`
COLON:              `:`
LF:                 `\n`
SPACE:              `     `
LITERAL:            `level3`
COLON:              `:`
LF:                 `\n`
SPACE:              `       `
DASH:               `-`
SPACE:              ``
LITERAL:            `item1`
LF:                 `\n`
SPACE:              `       `
DASH:               `-`
SPACE:              ``
LITERAL:            `item2`
LF:                 `\n`
SPACE:              `       `
DASH:               `-`
SPACE:              ``
LITERAL:            `key`
COLON:              `:`
LITERAL:            `value`
LF:                 `\n`
LF:                 `\n`
```