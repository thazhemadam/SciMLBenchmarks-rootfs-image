# Rootfs Images

```bash
julia --project rootfs-script.jl --arch amd64

# to identify the treehash for a rootfs image.
if [ ! -d "../rootfs-images" ]; then
    git clone git@github.com:JuliaCI/rootfs-images.git ../rootfs-images
fi

```
