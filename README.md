# astral yaml

A YAML lexer written in [Astral](https://github.com/fuseraft/astral).

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
1: 0: LITERAL: `server`
1: 0: COLON: `:`
2: 2: LITERAL: `host`
2: 2: COLON: `:`
2: 2: LITERAL: `localhost`
3: 2: LITERAL: `port`
3: 2: COLON: `:`
3: 2: NUMERIC_LITERAL: `8080`
4: 2: LITERAL: `enabled`
4: 2: COLON: `:`
4: 2: LITERAL: `true`
6: 0: LITERAL: `database`
6: 0: COLON: `:`
7: 2: LITERAL: `host`
7: 2: COLON: `:`
7: 2: LITERAL: `db.local`
8: 2: LITERAL: `port`
8: 2: COLON: `:`
8: 2: NUMERIC_LITERAL: `5432`
9: 2: LITERAL: `username`
9: 2: COLON: `:`
9: 2: LITERAL: `admin`
10: 2: LITERAL: `password`
10: 2: COLON: `:`
10: 2: LITERAL: `secret`
11: 2: LITERAL: `settings`
11: 2: COLON: `:`
12: 4: DASH: `-`
12: 4: LITERAL: `connections`
12: 4: COLON: `:`
12: 4: NUMERIC_LITERAL: `10`
13: 4: DASH: `-`
13: 4: LITERAL: `timeout`
13: 4: COLON: `:`
13: 4: NUMERIC_LITERAL: `30`
14: 4: DASH: `-`
14: 4: LITERAL: `lazyLoad`
14: 4: COLON: `:`
14: 4: LITERAL: `true`
16: 0: LITERAL: `services`
16: 0: COLON: `:`
17: 2: DASH: `-`
17: 2: LITERAL: `name`
17: 2: COLON: `:`
17: 2: LITERAL: `userservice`
18: 4: LITERAL: `url`
18: 4: COLON: `:`
18: 4: LITERAL: `http://localhost:8000/users`
19: 4: LITERAL: `methods`
19: 4: COLON: `:`
20: 6: DASH: `-`
20: 6: LITERAL: `GET`
21: 6: DASH: `-`
21: 6: LITERAL: `POST`
22: 2: DASH: `-`
22: 2: LITERAL: `name`
22: 2: COLON: `:`
22: 2: LITERAL: `paymentservice`
23: 4: LITERAL: `url`
23: 4: COLON: `:`
23: 4: LITERAL: `http://localhost:8001/pay`
24: 4: LITERAL: `methods`
24: 4: COLON: `:`
25: 6: DASH: `-`
25: 6: LITERAL: `POST`
27: 0: LITERAL: `logging`
27: 0: COLON: `:`
28: 2: LITERAL: `level`
28: 2: COLON: `:`
28: 2: LITERAL: `debug`
29: 2: LITERAL: `format`
29: 2: COLON: `:`
29: 2: QUOTED: `[%d{HH:mm:ss}] [%t] %-5level - %msg%n`
30: 2: LITERAL: `destinations`
30: 2: COLON: `:`
31: 4: DASH: `-`
31: 4: LITERAL: `console`
32: 4: DASH: `-`
32: 4: LITERAL: `file`
33: 4: DASH: `-`
33: 4: LITERAL: `syslog`
35: 0: LITERAL: `nested_structures`
35: 0: COLON: `:`
36: 2: LITERAL: `level1`
36: 2: COLON: `:`
37: 4: LITERAL: `level2`
37: 4: COLON: `:`
38: 6: LITERAL: `level3`
38: 6: COLON: `:`
39: 8: DASH: `-`
39: 8: LITERAL: `item1`
40: 8: DASH: `-`
40: 8: LITERAL: `item2`
41: 8: DASH: `-`
41: 8: LITERAL: `key`
41: 8: COLON: `:`
41: 8: LITERAL: `value`
```