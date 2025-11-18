### zarr-datafusion-search-examples

Notebook examples to demonstrate the functionality of [zarr-datafusion-search](https://github.com/developmentseed/zarr-datafusion-search).

Currently, Icechunk virtual chunk container support for requester pays buckets relies on this experimental [icechunk branch](https://github.com/developmentseed/icechunk/tree/smithy_requester_pays) but a PR for this should be landing shortly.

To run the examples you'll currently need to build icechunk and zarr-datafusion-search using the above branch and update `pyproject.toml` with the local location of the wheels.

Then
```
uv run --with jupyter jupyter lab
```
