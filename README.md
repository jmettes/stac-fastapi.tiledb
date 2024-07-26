Experiment for testing [stac-fastapi](https://github.com/stac-utils/stac-fastapi) frontend for a TileDB database in S3

---

Testing environment

```
$ pip install -e .docker run -p 7654:7654 -v $(pwd):/var/task --entrypoint /bin/bash -it amazon/aws-lambda-python:3.12
$ pip install -e .
$ stac-fastapi-tiledb
```

Open localhost:7654 in browser