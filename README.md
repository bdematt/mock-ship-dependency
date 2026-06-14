# Mock Ship Dependency

## Create a Dev Org

Spin up a personal scratch org with your source deployed and dependencies installed:

```
sf ship flow run deploy/dev
```

## Retrieve Metadata

After making changes in the org, pull them back locally:

```
sf project retrieve start
```

## Create a Release

Build and promote a new package version through environments:

```
sf ship flow run deploy/beta
```

## Promote a Package Version

```
sf ship flow run promote
```

## Documentation

TODO
