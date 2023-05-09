Sphinx References Test
======================

Serving HTML files
------------------

```bash
# Using Caddy
caddy start

# Now, visit https://localhost:2000

# and to stop afterwards
caddy stop
```

Rebuilding HTML files
---------------------

```bash
# Install pip dependencies (using pipenv)
pipenv sync

# Build docs
pipenv run sphinx-build -C ./docs ./out
```
