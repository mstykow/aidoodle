To transpile the typescript code:

```bash
tsc --strictNullChecks -p tsconfig.json
# or
tsc --strictNullChecks -p tsconfig.json -w  # daemon
```

To run a server and check the outcome:

```bash
python server.py
firefox http://0.0.0.0:8080/src/static/index.html
```

To run tests, from the typescript root, run:

```bash
yarn jest
```
