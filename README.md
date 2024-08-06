# protoc-gen-go-topics

## Usage

`go install github.com/isfk/protoc-gen-go-topics@latest`

### Buf

```yaml
# buf.yaml
plugins:
  - local: protoc-gen-go-topics
    out: gen/go
    opt: paths=source_relative

# buf.gen.yaml
deps:
  - buf.build/isfk/topics
```

## example

```sh
cd example

buf generate
```