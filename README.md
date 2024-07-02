Protobuf definitions for various projects, including [swift-homomorphic-encryption](https://github.com/apple/swift-homomorphic-encryption-protobuf)

## Contributing

Before contributing, please run [`pre-commit`](https://pre-commit.com), e.g. via `pre-commit run --all-files`. This will perform some basic formatting checks.

To install `pre-commit`, follow instructions in https://pre-commit.com/. We recommend `brew install pre-commit`.

## Test

To test your changes, generate the protos using `protoc` in a tmp folder.

```bash
protoc --python_out /tmp *.proto
```
