
## Generate doc

```
cd sst
cargo doc --no-deps --open
```
## Build and Run

```
cd sst
cargo run --target-dir "$HOME/rustbuld/${PWD##*/}"
```

## Other useful
check
clean
build
fmt

add -r to build for release

##Script
./sst.sh check