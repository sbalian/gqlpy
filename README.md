# gqlpy

Lightweight client for GraphQL in Python.

```bash
pip install gqlpy
```

Set the two environment variables:

1. `GQLPY_URL` for the URL.
2. `GQLPY_TOKEN` for the authorization token.

You can also set these in `.env`.

Then:

```python
import gqlpy

query: str = ... # your GraphQL query

json_response = gqlpy.post(query)
```