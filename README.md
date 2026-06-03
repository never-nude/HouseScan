# HouseScan

Recovered HouseScan exterior-home 3D scan exports from Google Drive.

This repository contains two recovered scan artifacts:

- A textured USDZ photogrammetry reconstruction for the front exterior segment.
- A rough LiDAR OBJ mesh export for the back exterior segment.

The USDZ can be opened with Apple's Preview/Quick Look, Reality Composer Pro, Blender with USD support, or another USDZ viewer. The OBJ can be opened in Blender, MeshLab, or another OBJ viewer.

## Files

- `assembled-clean/Kushman House.usdz` - textured front exterior photogrammetry reconstruction.
- `assembled-clean/reconstruction-summary.json` - USDZ reconstruction summary and checksum.
- `assembled-clean/source-metadata.json` - source photo-capture metadata.
- `assembled-clean/source-field-test-log.json` - source photo-capture field-test log.
- `Back-LiDAR-HouseScan.obj` - rough back exterior LiDAR geometry OBJ export.
- `lidar-mesh.mtl` - material file referenced by the OBJ.
- `lidar-mesh-summary.json` - LiDAR mesh export counts and source artifact paths.
- `metadata.json` - LiDAR capture/export metadata from the field test.
- `README.txt` - original LiDAR README recovered from Google Drive.

## Front Photogrammetry Scan

- Segment: Front
- Capture mode: Photo Capture
- Source images: 135
- Source image resolution: 4032x3024
- Photogrammetry detail: reduced
- Output USDZ size: 16,413,346 bytes
- Output USDZ SHA-256: `8825c7932e93b75e459f566b854dda9061cc58fbb0e27c1ae133ea0097cbeef2`
- Capture start: 2026-05-01 at 19:14:07Z
- Capture stop: 2026-05-01 at 19:20:53Z

## Back LiDAR Mesh

- Segment: Back
- Capture mode: LiDAR House Scan
- Surface count: 267
- Vertices: 760,682
- Faces: 1,346,541
- OBJ size: 54,747,027 bytes
- Approximate bounds: 27.071m x 8.308m x 36.500m

The capture metadata records the scan starting on 2026-05-01 at 18:23:21Z and completing export on 2026-05-01 at 18:27:43Z.
