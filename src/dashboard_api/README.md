# API
The Dashboard API Component implements the API for *UI*

## Start with dummy data
For development purposes you may want to start the API with some dummy data. Make sure you have setup  your development environment like described in [our developer guide](/docs/dev.md).

First start `postgres` and `minio` with some [dummy data](/infrabox/utils/storage):

```bash
./ib.py services start storage
```

Now start the API:

```bash
./ib.py services start dashboard_api
```

The API Server starts up on port 8082.

## API Docs
After you have started the API you can access the docs at http://localhost:8082/doc