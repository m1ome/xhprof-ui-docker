# Info
Docker with apache & PHP to view XHprof reports.

## Building
```bash
make build
```

## Usage
```bash
    docker run --rm -p 9080:80 -d -v <path_to_your_reports>:/tmp xhprof:latest
```