# pokestarbot-v1 Docker

Source: https://github.com/PythonCoderAS/pokestarbot-v1

## Running

```bash
docker run -v `/some/path:/app/bot_data/creds.py` -v `bot-data:/app/bot_data/database.db` ghcr.io/pythoncoderas/pokestarbot-v1
```

## Prerequisites

Follow the instructions in the parent repo.

### Mappings

* `/some/path:/app/bot_data/creds.py`
* `/some/other/path:/app/bot_data/database.db` (Recommended to make this a volume)
