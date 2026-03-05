# centy-io/proto

Protocol Buffer definitions for the Centy daemon gRPC API.

## Consuming this repo

This repository is intended to be consumed as a git submodule:

```sh
git submodule add https://github.com/centy-io/proto proto
```

## Structure

```
centy/v1/
  centy.proto        # CentyDaemon service and message types
  generic_item.proto # Shared generic item messages
```
