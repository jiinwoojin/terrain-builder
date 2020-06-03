# jiinwooin/terrain-builder
cesium-terrain-builder

# 실행 스크립트
docker run --rm --user {UID}:{GID} -v /data/jiapp:/data/jiapp --name jimap_terrain_builder jiinwooin/jimap_terrain_builder ctb-tile -f Mesh -C -N -o {output dir} {input file}

docker run --rm --user {UID}:{GID} -v /data/jiapp:/data/jiapp --name jimap_terrain_builder jiinwooin/jimap_terrain_builder ctb-tile -f Mesh -l -C -N -o {output dir} {input file}