# jiinwooin/terrain-builder
cesium-terrain-builder

# 실행 스크립트
docker run --rm -v /data/jiapp:/data/jiapp --name builder jiinwooin/terrain-builder ctb-tile -f Mesh -C -N -o {output dir} {input file}

docker run --rm -v /data/jiapp:/data/jiapp --name builder jiinwooin/terrain-builder ctb-tile -f Mesh -l -C -N -o {output dir} {input file}