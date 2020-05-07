# Docker file

```
make image
docker run --rm -v `pwd`:/project -it amethyst:v0.1 /bin/bash

#inside the container:
source ~/.cargo/env
cargo build --features vulkan
```